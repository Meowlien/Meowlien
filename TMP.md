# Meowlien Studio
`URL: https://www.meowlien.com (構建中)`

For Windows : ( D:\> ) Data Driver
For Linux   : User\Data\

## Index 目錄
```
.
├── Meowlien (Home)
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
.   .   .   ├── TypeScript
.   .   .   └── CoffeeScript
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
.   .   .   .
.   .   .   @ 程式語言
.   .   .   ├── learn-lan-Assembly      (.asm) // 組合語言: 直接控制硬體的超底層程式語言
.   .   .   ├── learn-lan-c             (.c)
.   .   .   ├── learn-lan-cpp (C++)     (.cpp)
.   .   .   ├── learn-lan-csharp (C#)   (.cs)
.   .   .   .   ├── learn-ASP.Net
.   .   .   .   └── ...
.   .   .   ├── learn-lan-java          (.py)
.   .   .   ├── learn-lan-python
.   .   .   .   ├── learn-python2_7     // 過時
.   .   .   .   ├── learn-python3
.   .   .   .   └── ...
.   .   .   ├── learn-lan-javascript    (.js)
.   .   .   .   ├── learn-typescript    (.ts)
.   .   .   .   ├── learn-coffeescript  (.coffee)
.   .   .   .   └── ...
.   .   .   ├── learn-lan-golang (go)   (.go)
.   .   .   ├── learn-lan-Ruby          (.rb) // 統計學
.   .   .   ├── learn-lan-Perl          (.pl | .pm 包含模組) // 自動化脚本, 與 python 很像
.   .   .   .
.   .   .   @ 資料庫
.   .   .   ├── learn-dbs-Databases ( Table, Row, Column, Key ... )
.   .   .   .
.   .   .   @ 查詢語言
.   .   .   ├── learn-query-sql ( select ... from ... where ... )
.   .   .   ├── learn-query-nosql ( sql 的拓展, 意為不只有sql )
.   .   .   .
.   .   .   @ 標簽語言
.   .   .   ├── learn-lbl-html 網頁
.   .   .   ├── learn-lbl-xml [link](learn-net-packet/learn-xml)
.   .   .   .
.   .   .   @ 樣式語言
.   .   .   ├── learn-sty-css
.   .   .   ├── learn-sty-qss (For Qt)
.   .   .   .
.   .   .   @ 脚本語言
.   .   .   ├── learn-scr-batch [link](learn-sys-windows/learn-batch)
.   .   .   ├── learn-scr-shell [link](learn-sys-linux/learn-shell)
.   .   .   .
.   .   .   @ 軟體工程
.   .   .   ├── learn-soft-algorithm 演算法
.   .   .   ├── learn-soft-struct 結構式程式設計
.   .   .   ├── learn-soft-OOP 物件導向程式設計
.   .   .   ├── learn-soft-multithreading 多執行緒(多工) / 平行計算
.   .   .   ├── learn-soft-asynchronous 非同步 / 效率
.   .   .   .
.   .   .   @ 資訊安全
.   .   .   ├── learn-cryp-hash 哈希函數
.   .   .   ├── learn-cryp-DES 對稱加密
.   .   .   ├── learn-cryp-RSA 非對稱加密
.   .   .   ├── learn-cryp-SSH 加密殼
.   .   .   ├── learn-cryp-SSL 數位憑證
.   .   .   ├── learn-cryp-blockChain 區塊鏈 / 加密貨幣
.   .   .   .
.   .   .   @ 人工智慧
.   .   .   ├── learn-AI-artificialNeuralNetwork 内神經網路
.   .   .   ├── learn-AI-naturalLanguageProcessing 自然語言處理
.   .   .   ├── learn-AI-computerVision 計算機視覺
.   .   .   ├── learn-AI-machineLearning 機器學習 / 行爲決策
.   .   .   ├── learn-AI-deepLearning 深度學習
.   .   .   .
.   .   .   @ 大數據 & 超大數據
.   .   .   ├── learn-bdat-dataMining 資料探勘
.   .   .   ├── learn-bdat-dataAnalyze 數據分析
.   .   .   ├── learn-bdat-dataVisualization 數據視覺化
.   .   .   ├── learn-bdat-machineLearning 機器學習 / 數據模型(訓練)
.   .   .   .
.   .   .   @ 網路工程
.   .   .   ├── learn-net-hardware 網路設備 (modem, router, switch...)
.   .   .   ├── learn-net-theory 理論 (IP, Port, Protocol...)
.   .   .   ├── learn-net-packet 封包
.   .   .   .   @ 資料格式
.   .   .   .   ├── learn-json
.   .   .   .   ├── learn-yaml
.   .   .   .   ├── learn-xml
.   .   .   .   ├── learn-protobuf
.   .   .   .   └── ...
.   .   .   ├── learn-net-socket 通訊
.   .   .   ├── learn-net-firewall 防火墻
.   .   .   .
.   .   .   @ 系統工程 - 軟體層面
.   .   .   ├── learn-sys-linux         (音譯: 拎勒斯) 沒中文名
.   .   .   .   ├── learn-shell
.   .   .   .   ├── Configuration
.   .   .   .   └── ...
.   .   .   ├── learn-sys-windows       微軟系統
.   .   .   .   ├── learn-batch
.   .   .   .   └── ...
.   .   .   ├── learn-sys-macOSX        蘋果系統 PC
.   .   .   ├── learn-sys-ios           蘋果系統 iPhone
.   .   .   ├── learn-sys-android       安卓系統
.   .   .   ├── learn-sys-iPadOS        蘋果系統 Pad
.   .   .   ├── learn-sys-watchOS       蘋果系統 iWatch
.   .   .   ├── learn-sys-tvOS          蘋果系統 TV
.   .   .   .
.   .   .   @ 系統工程 - 虛擬層面 (系統裏面的系統)
.   .   .   ├── learn-sys-containers    容器
.   .   .   .
.   .   .   @ 系統工程 - 硬體層面
.   .   .   ├── learn-sys-computerStructure 計算機結構
.   .   .   ├── learn-sys-instructionSet 指令集 (x86架構-複雜指令集, arm架構-精簡指令集)
.   .   .   ├── learn-sys-bandwidth 帶寬 (32位系統, 64位系統)
.   .   .   ├── learn-sys-complier 編譯器
.   .   .   ├── learn-sys-embeddedSystems 嵌入式系統
.   .   .   .   ├── learn-arduino (音譯: 啊度摟) 沒中文名
.   .   .   .   ├── learn-raspberryPi 樹莓派系統
.   .   .   .   └── ...
.   .   .   └── ...
.   .   .
.   .   ├── Projects 專案項目 (Private)
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
.   .   .   ├── [ ] [PK]  packet-Schema         (grpc, ProtoBuf)    { X }
.   .   .   ├── [ ] [EP] lineBot-Meowlien       (Flask, Python)     { X }
.   .   .   ├── [ ] [FP]     web-MeowlienStudio (Vue, TypeScript)   { Website }
.   .   .   ├── [ ] [EP]     svc-ServiceGuard   (ASP.NET, C#)       { X }
.   .   .   ├── [ ] [EP]     svc-PosService     (Qt, C++)           { Windows }
.   .   .   ├── [ ] [EP]     sys-SystemStarter  (Qt, C++)           { Windows }
.   .   .   ├── [ ] [FE]     app-Pos            (Qt, C++)           { PC, Phone, Pad }
.   .   .   ├── [ ] [FE]     app-Accounting     (Qt, C++)           { PC, Phone, Pad }
.   .   .   ├── [*] [FE]    game-Trainer        (Unity3D, C#)       { PC, Phone, Pad }
.   .   .   ├── [ ] [EP]      db-Meowlien       (SQL, PostgresSQL)  { X }
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