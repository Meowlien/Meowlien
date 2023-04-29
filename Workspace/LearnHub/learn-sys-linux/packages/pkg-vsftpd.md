# Package - vsftpd
`Very Secure FTP Daemon`

#### 説明
> 注重安全的 FTP(File Transfer Protocol) 守護進> 程軟體包。

#### 安裝指令
``` sh
# Arch Linux
sudo pacman -S vsftpd
```

配置檔位置
``` makefile
/etc/vsftpd.conf

# 配置列表
ssl_enable=YES
rsa_cert_file=/etc/ssl/certs/vsftpd.crt
rsa_private_key_file=/etc/ssl/private/vsftpd.key
ssl_tlsv1=YES
ssl_sslv2=NO
ssl_sslv3=NO
require_ssl_reuse=NO
ssl_ciphers=HIGH
```

自簽證書 (有效期 365天)
``` sh
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/ssl/private/vsftpd.key -out /etc/ssl/certs/vsftpd.crt
```

系統指令
``` sh
sudo systemctl start vsftpd     # 啓動
sudo systemctl restart vsftpd   # 重啓
```

``` makefile
anonymous_enable=YES                            # 开放匿名用户
local_enable=YES                                # 可使用ftp服务器上面的本地用户，vipw查看
write_enable=YES                                # 是否允许本地用户对FTP服务器文件具有写权限
local_umask=022                                 # 本地用户对FTP服务器文件具有写权限，掩码，022实际644
# ----------------------------------------------- 文件默认权限=666-umask值 666-022=644
# ----------------------------------------------- 目录默认权限=777-umask值 777-022=755
#anon_upload_enable=YES                         # 匿名可上传
#anon_mkdir_write_enable=YES                    # 匿名可创建新文件夹
dirmessage_enable=YES                           # 欢迎信息
xferlog_enable=YES                              # 上传下载，记录日志
connect_from_port_20=YES                        #
chown_uploads=YES                               # 对匿名上传文件的所有者进行更改
#chown_username=whoever                         #
#xferlog_file=/var/log/xferlog                  # 日志路径
xferlog_std_format=YES                          #
#idle_session_timeout=600                       # 空闲600秒断开
#data_connection_timeout=120                    # 数据连接超时时间为120秒断开
#nopriv_user=ftpsecure                          #
#async_abor_enable=YES                          #
#ascii_upload_enable=YES                        # 采用ASCII方式传输数据，对大文件比较好，但可能会导致DoS攻击
#ascii_download_enable=YES                      #
#ftpd_banner=Welcome to blah FTP service.       # 欢迎词
#deny_email_enable=YES                          # 匿名登陆，设置禁用的email
#banned_email_file=/etc/vsftpd/banned_emails    #
#chroot_local_user=YES                          # YES的话，本地用户只能留在自己的目录~里面， 建议打开
# ----------------------------------------------- (高版本默认的目录不能有写权限, 或allow_writeable_chroot=YES)
#chroot_list_enable=YES                         # 与#chroot_local_user一起配合
#chroot_list_file=/etc/vsftpd/chroot_list       #默认可以切换目录的用户
#ls_recurse_enable=YES                          # 是否允许递归查询。默认为关闭，以防止远程用户造成过量的I/O
listen=YES                                      # 监听ipv4, ipv4,ipv6只能选1，两个都监听再运行一个vsftpd
#listen_ipv6=YES                                # 监听ipv6
pam_service_name=vsftpd                         # /etc/pam.d/vsftpd 验证规则
userlist_enable=YES                             # userlist_file=/etc/vsftp/user_list
#userlist_deny=YES                              # 默认为YES, 
# ----------------------------------------------- YES，则user_list用户不能将登录FTP
# ----------------------------------------------- NO,  则user_list用户才能访问
tcp_wrappers=YES                                # 可以在/etc/hosts.allow, host.deny增加拒绝名单
```