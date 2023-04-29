

```
For Windows : ( D:\> ) Data Driver
For Linux   : User\Data\
.
├── Meowlien
.   .
.   ├── Database 資料庫
.   ├── Document 文件
.   ├── Environment 環境
.   .   .
.   .   ├── Database 資料庫環境
.   .   .   ├── PostgreSQL
.   .   .   ├── Microsoft SQL Server
.   .   .   ├── MySQL
.   .   .   └── Redis
.   .   .
.   .   ├── Framework 框架
.   .   .   ├── Qt ( For cpp, python)
.   .   .   ├── Dot Net Core ( For C# )
.   .   .   ├── UnityEngine ( For C# )
.   .   .   └── Vue.js ( For javascript, typescript )
.   .   .
.   .   ├── Others 其他環境
.   .   .   ├── [Git] Git / PortableGit(GUI)
.   .   .   ├── [SDK] google-cloud-sdk
.   .   .   ├── [RPC] grpc
.   .   .   ├── [Security] OpenSSL
.   .   .   └──
.   .   .
.   .   ├── PLanguage 語言環境
.   .   .   ├── C_CPP
.   .   .   ├── CSharp
.   .   .   ├── Java
.   .   .   ├── Python
.   .   .   ├── JavaScript
.   .   .   └── TypeScript
.   .   .
.   .   ├── System 系統環境 ( Only for Windows )
.   .   .   ├── wsl-ArchLinux
.   .   .   .   └── Configuration [mklink](/Workspace/LearnHub/learn-Linux/Configuration)
.   .   .   .
.   .   .   └── wsl-XXX
.   .   .
.   .   ├── Tools 工具 
.   .   .   ....................................................................
.   .   .   +   [A] 美術
.   .   .   +   [F] 前端
.   .   .   +   [E] 後端
.   .   .   +   [*] 基礎(必裝)
.   .   .   +   [-] 可選(選裝)
.   .   .   +   [ ] 無需
.   .   .   ....................................................................
.   .   .   @   [A] [F] [E] [類別] 工具名稱
.   .   .   ....................................................................
.   .   .   ├── [ ] [-] [*] [IDE] Visual Studio
.   .   .   ├── [ ] [-] [*] [IDE] Android Studio
.   .   .   ├── [*] [*] [-] [Engine] Unity3D
.   .   .   ├── [-] [-] [-] [Engine] Cocos
.   .   .   ├── [*] [ ] [ ] [Engine] Blender
.   .   .   ├── [-] [ ] [ ] [Engine] 3DsMax
.   .   .   ├── [-] [ ] [ ] [Engine] Maya
.   .   .   ├── [*] [*] [*] [Code] Visual Studio Code
.   .   .   ├── [ ] [ ] [*] [System] WSL2
.   .   .   ├── [ ] [ ] [*] [Make] CMake
.   .   .   ├── [ ] [ ] [*] [DB] pgAdmin4
.   .   .   ├── [ ] [ ] [*] [DB] Microsoft SQL Server Management Studio
.   .   .   ├── [ ] [ ] [-] [DB] MySQL Workbench
.   .   .   ├── [ ] [ ] [*] [DB] Another Redis Desktop Manager
.   .   .   ├── [-] [*] [*] [Remote] RDCMan
.   .   .   ├── [*] [*] [*] [Remote] Chrome Extension RDC
.   .   .   ├── [ ] [ ] [*] [Network] WireShark
.   .   .   ├── [ ] [ ] [*] [Network] TCPView
.   .   .   ├── [*] [*] [*] [Security] PuTTY
.   .   .   ├── [*] [*] [*] [Security] MD5Summer
.   .   .   ├── [-] [-] [*] [FTP] WinSCP
.   .   .   ├── [*] [*] [*] [FTP] FileZilla Client
.   .   .   ├── [ ] [ ] [*] [FTP] FileZilla Server
.   .   .   ├── [-] [-] [*] [Git] GitKraken
.   .   .   ├── [*] [*] [*] [Git] TortoiseGit
.   .   .   ├── [*] [*] [*] [Other] 7z
.   .   .   └── [ ] [ ] [ ] [] 
.   .   .
.   .   └── ...
.   .
.   ├── Permission 資訊安全
.   └── Workspace 工作區
.   .   ├── LearnHub 學習中心
.   .   .   ├── learn-lan-c
.   .   .   ├── learn-lan-cpp
.   .   .   ├── learn-lan-csharp
.   .   .   ├── learn-lan-python
.   .   .   ├── learn-lan-sql
.   .   .   ├── learn-lan-html-css
.   .   .   ├── learn-lan-javascript
.   .   .   ├── learn-lan-typescript
.   .   .   ├── learn-lan-batch [link](learn-sys-windows/learn-batch)
.   .   .   ├── learn-lan-shell [link](learn-sys-linux/learn-shell)
.   .   .   ├── learn-sys-linux
.   .   .   .   ├── learn-shell
.   .   .   .   ├── Configuration
.   .   .   .   └── ...
.   .   .   .
.   .   .   ├── learn-sys-windows
.   .   .   .   ├── learn-batch
.   .   .   .   └── ...
.   .   .   .
.   .   .   └── ...
.   .   .
.   .   ├── Projects 專案項目
.   .   .   ....................................................................
.   .   .   +   [FP] 前端
.   .   .   +   [EP] 後端
.   .   .   +   [FE] 全端
.   .   .   +   [PK] 封包
.   .   .   +   [*]  當前
.   .   .   ....................................................................
.   .   .   +   lineBot-    line 機器人
.   .   .   +       web-    網站
.   .   .   +       svc-    服務器
.   .   .   +       app-    軟體
.   .   .   +      game-    游戲
.   .   .   +        db-    資料庫
.   .   .   +    packet-    封包定義
.   .   .   ....................................................................
.   .   .   @   [ ] [  ] 類別-項目名稱 (框架, 語言) { 目標平臺 }
.   .   .   ....................................................................
.   .   .   ├── [ ] [PK]  packet-Schema        (grpc, ProtoBuf)    { X }
.   .   .   ├── [ ] [EP] lineBot-Meowlien      (Flask, Python)     { X }
.   .   .   ├── [ ] [FP]     web-Meowlien      (Vue, TypeScript)   { Website }
.   .   .   ├── [ ] [EP]     svc-ServiceGuard  (ASP.NET, C#)       { X }
.   .   .   ├── [ ] [EP]     svc-PosService    (Qt, C++)           { Windows }
.   .   .   ├── [ ] [EP]     sys-SystemStarter (Qt, C++)           { Windows }
.   .   .   ├── [ ] [FE]     app-Pos           (Qt, C++)           { PC, Phone, Pad }
.   .   .   ├── [ ] [FE]     app-Accounting    (Qt, C++)           { PC, Phone, Pad }
.   .   .   ├── [*] [FE]    game-Trainer       (Unity3D, C#)       { PC, Phone, Pad }
.   .   .   ├── [ ] [EP]      db-Meowlien      (SQL, PostgresSQL)  { X }
.   .   .   └── [ ]
.   .   .
.   .   └── Utils 輔助工具
.   .
.   └── ...
.
└── End
```


```
( C:\> ) System Driver Link
.
├── Meowlien => Meowlien
├── Database => Database
└── Environment => Environment
```

```
Eagle
.
├── Eagle ： 極度占用空間
├── Digikam
├── 
├── 
└── 

```