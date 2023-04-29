# learn-shell

## `sed <選項> <命令> [文件]`
説明：該命令僅輸出替換後的文本數據流，不會修改原始數據

#### <選項>
| Cmd | Description
|:---:|:------------------------
|  d  | 刪除輸入數據流中的行
|  p  | 打印輸入數據流中的行
|  a  | 在輸入數據流中的行後添加文本
|  i  | 在輸入數據流中的行前添加文本

#### <命令>
| Cmd            | Description
|:--------------:|:---------------------
|  s/StrA/StrB/  | StrB 替換 StrA

## `cat [選項] [文件...]`
説明：查看，合并文本文件

``` sh
cat <<EOT > filename
text
EOT
```
| Cmd  | Description
|:----:|:------------------------
| text | 多行文本
| EOT  | End of Text

> 範例：將文本寫入 example.txt
> ``` txt
> Hello world!
> This is an example file.
> ```
> ``` sh
> cat <<EOT > example.txt
> Hello world!
> This is an example file.
> EOT
> ```

`sysctl -p` 用於重新加載配置檔
> /etc/sysctl.conf
> /etc/sysctl.d/*

`touch <選項> <文件名>...` 創建空文件
`useradd <選項> <用戶名>` 創建新賬戶
`passwd <用戶名>` 為該用戶設置密碼
`mkdir <選項> <目錄名>...` 創建一個或多個新目錄
`chown <選項> <所有者><:所屬群> <文件名>` 更改文件或目錄的所有者和所屬群
`usermod <選項> <用戶名>` 修改用戶的屬性
`chmod <選項> <權限> <文件名>...` 修改文件或目錄權限

`su <用戶名>` 切換用戶



