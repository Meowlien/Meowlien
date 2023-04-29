# ArchLinux

`cd /` 根目錄


指令

`pacman -Q` 已安裝的 pack 列表

`pacman --noconfirm` 不詢問確認，自動安裝

---

`pacman -Su`
```
[ 下載及更新 ] 檢查已安裝 pack 是否需要更新，有則下載，安裝更新
```
<br>

`pacman -Sy <pack>`
```
[ 下載 ] 檢查已安裝 pack 是否需要更新，有則下載，但不做安裝更新的動作
```
<br>

`pacman -Syu`
```
[ 下載及更新 ] 將所有已安裝 pack 更新到最新版，包括：内核、驅動、等系統組件
```
<br>

---

`pacman -S, --sync <pack>`
```
[ 安裝包 ]: 從遠端 pack 倉庫中，安裝指定的 pack
```
<br>

`pacman -U, --upgrade <path/pack.pkg.tar.zst>`
```
[ 指定包 ]: 指定路徑下的 pack 進行安裝
```
<br>

`pacman -R, --remove <pack>`
```
[ 刪除包 ]: 從系統中卸載指定 pack，移除依賴項，刪除相關配置及脚本
```
<br>

`pacman -Sc`
```
清理當前未被安裝的 pack 緩存：
/var/cache/pacman/pkg 目錄下的所有 pack 文件
```
<br>

`pacman -Scc`
```
完全清理 pack 缓存:
/var/cache/pacman/pkg 目錄下的所有 pack 文件
/var/lib/pacman/sync  目錄下的所有 pack 數據庫文件
```
<br>

pacman-key
---
`pacman-key --init`
```
[ 生成本地憑證 ] 初始化 Pacman 密鑰，生成密鑰，用於後續 pack 簽章驗證
```
<br>

`pacman-key --populate`
```
[ 更新 pack 憑證 ] 從官方倉庫下載行的 GnuPG 密鑰，添加到本地
```
<br>


---

軟件包
`archlinux-keyring` 官方發行的 pack 簽名，相當於數位簽章
`catatonit`         以 golang 編寫的開源，輕量級容器引擎
`fuse-overlayfs`    可寫容器系統，用於修改容器内的文件
`kubectl`           Kubernetes 命令工具，群集管理，例如 pod...
`kubectx`           Kubernetes 的上下文切換工具
`k9s`               Kubernetes 用戶在終端管理和監控群集
`git`               git
`podman`            容器引擎
`buildah`           容器鏡像構建工具
`vsftpd`            FTP

系統
`update-ca-trust`   CA 證書列表 更新
`touch /etc/subuid` 儲存子用戶 ID
`touch /etc/subgid` 儲存子用戶組 ID


