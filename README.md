# Meowlien Studio
`URL: https://www.meowlien.com (構建中)`
`Router: /api/LearnHub`
```
.
├── LearnHub 學習中心
.   .
.   @ 程式語言
.   ├── learn-lan-Assembly      (.asm)  // 組合語言: 直接控制硬體的超底層程式語言
.   ├── learn-lan-c             (.c)
.   ├── learn-lan-cpp (C++)     (.cpp)
.   ├── learn-lan-csharp (C#)   (.cs)
.   .   ├── learn-ASP.Net
.   .   └── ...
.   ├── learn-lan-java          (.py)
.   ├── learn-lan-python
.   .   ├── learn-python2_7             // 過時
.   .   ├── learn-python3
.   .   └── ...
.   ├── learn-lan-javascript    (.js)       // 用於: 前端開發，尤其是 Web 開發
.   .   ├── learn-typescript    (.ts)       // 嚴謹版的 js
.   .   ├── learn-coffeescript  (.coffee)   // 簡單版的 js
.   .   └── ...
.   ├── learn-lan-golang (go)   (.go)
.   ├── learn-lan-Ruby          (.rb)   // 用於: 統計學
.   ├── learn-lan-Perl          (.pl)   // 用於: 自動化脚本，與 python 很像
.   .
.   @ 資料庫
.   ├── learn-dbs-Databases             // Table, Row, Column, Key ...
.   .
.   @ 查詢語言
.   ├── learn-query-sql                 // select ... from ... where ...
.   ├── learn-query-nosql               // sql 的拓展, 意為不只有 sql，還有更多功能
.   .
.   @ 標簽語言
.   ├── learn-lbl-html                  // 用於: 網頁開啊發
.   ├── learn-lbl-xml [link](learn-net-packet/learn-xml)
.   .
.   @ 樣式語言 (樣式定義，排版、美術等)
.   ├── learn-sty-css                   // 常用於: 網頁美術
.   ├── learn-sty-qss                   // Qt 框架的樣式定義
.   .
.   @ 脚本語言 (用於系統自動化處理)
.   ├── learn-scr-batch [link](learn-sys-windows/learn-batch)
.   ├── learn-scr-shell [link](learn-sys-linux/learn-shell)
.   .
.   @ 軟體工程
.   ├── learn-soft-algorithm            // 演算法
.   ├── learn-soft-struct               // 結構式程式設計
.   ├── learn-soft-OOP                  // 物件導向程式設計
.   ├── learn-soft-multithreading       // 多執行緒(多工) / 平行計算
.   ├── learn-soft-asynchronous         // 非同步 / 效率
.   .
.   @ 資訊安全
.   ├── learn-cryp-hash                 // 哈希函數
.   ├── learn-cryp-DES                  // 對稱加密
.   ├── learn-cryp-RSA                  // 非對稱加密
.   ├── learn-cryp-SSH                  // 加密殼
.   ├── learn-cryp-SSL                  // 數位憑證
.   ├── learn-cryp-blockChain           // 區塊鏈 / 加密貨幣
.   .
.   @ 人工智慧
.   ├── learn-AI-artificialNeuralNetwork    // 内神經網路
.   ├── learn-AI-naturalLanguageProcessing  // 自然語言處理
.   ├── learn-AI-computerVision             // 計算機視覺
.   ├── learn-AI-machineLearning            // 機器學習 / 行爲決策
.   ├── learn-AI-deepLearning               // 深度學習
.   .
.   @ 大數據 & 超大數據
.   ├── learn-bdat-dataMining           // 資料探勘
.   ├── learn-bdat-dataAnalyze          // 數據分析
.   ├── learn-bdat-dataVisualization    // 數據視覺化
.   ├── learn-bdat-machineLearning      // 機器學習 / 數據模型(訓練)
.   .
.   @ 網路工程
.   ├── learn-net-hardware              // 網路設備 (modem, router, switch...)
.   ├── learn-net-theory                // 理論 (IP, Port, Protocol...)
.   ├── learn-net-packet                // 封包 (可以理解爲包裹)
.   .   @ 資料格式
.   .   ├── learn-json
.   .   ├── learn-yaml
.   .   ├── learn-xml
.   .   ├── learn-protobuf
.   .   └── ...
.   ├── learn-net-socket                // 通訊
.   ├── learn-net-firewall              // 防火墻
.   .
.   @ 系統工程 - 軟體層面
.   ├── learn-sys-linux                 // 沒中文名 (音譯: 拎勒斯)
.   .   ├── learn-shell
.   .   ├── Configuration
.   .   └── ...
.   ├── learn-sys-windows               // 微軟系統
.   .   ├── learn-batch
.   .   └── ...
.   ├── learn-sys-macOSX                // 蘋果系統 PC
.   ├── learn-sys-ios                   // 蘋果系統 iPhone
.   ├── learn-sys-android               // 安卓系統
.   ├── learn-sys-iPadOS                // 蘋果系統 Pad
.   ├── learn-sys-watchOS               // 蘋果系統 iWatch
.   ├── learn-sys-tvOS                  // 蘋果系統 TV
.   .
.   @ 系統工程 - 虛擬層面 (系統裏面的系統)
.   ├── learn-sys-containers            // 容器 (單一系統僅執行單一軟體，以確保穩定性)
.   .   ├── learn-docker                // 沒中文名 (形譯: 鯨魚)
.   .   ├── learn-podman                // 沒中文名 (形譯: 小鼴鼠)
.   .   └── ...
.   .
.   @ 系統工程 - 硬體層面
.   ├── learn-sys-computerStructure     // 計算機結構
.   ├── learn-sys-instructionSet        // 指令集 (x86架構-複雜指令集, arm架構-精簡指令集)
.   ├── learn-sys-bandwidth             // 帶寬 (32位系統, 64位系統)
.   ├── learn-sys-complier              // 編譯器
.   ├── learn-sys-embeddedSystems       // 嵌入式系統 (針對性開發的特殊系統)
.   .   ├── learn-IOT                   // 物聯網 / 智慧家居
.   .   ├── learn-arduino               // 沒中文名 (音譯: 啊度摟) / 機器人
.   .   ├── learn-raspberryPi           // 樹莓派系統 / 中控系統
.   .   └── ...
.   └── ...
└── End
```