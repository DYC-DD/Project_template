# Project_template

### 專案資料夾範本

方便未來啟動專案時取用。

---

### Python_Project_template

```
Project_template/
├── config/                        # 用於存放系統設定檔
│   ├── config.yaml                # 專案的配置文件，使用YAML格式存放全局設定參數
│   ├── key.env                    # 金鑰
│   ├── logging.conf               # 日誌設定檔，配置Python的日誌記錄器
│   └── settings.ini               # 系統或應用層面的配置文件，使用INI格式存放設置項
│
├── data/                          # 存放專案所需的數據集
│   ├── feature/                   # 特徵文件
│   ├── processed/                 # 處理過的數據文件
│   ├── raw/                       # 原始數據文件
│   └── cleaned_data.ipynb         # 資料處理
│
├── docs/                          # 存放專案的相關文檔，如API說明、設計文檔等
│
├── envs/                          # 用於存放環境設定相關文件
│   ├── Dockerfile                 # 用於建立Docker容器的設定檔，方便專案的容器化部署
│   └── environment.yml            # Conda環境的配置文件
│
├── src/                           # 存放專案的源代碼
│   ├── utils/                     # 存放常用的輔助函數或工具模組
│   │   └── __init__.py            # 使該目錄成為一個Python包
│   ├── __init__.py                # 使該目錄成為一個Python包
│   ├── main.py                    # 主程序入口，通常用於啟動應用
│   └── module.py                  # 各自實現不同功能的模組
│
├── tests/                         # 存放測試代碼
│   ├── __init__.py                # 使該目錄成為一個Python包
│   ├── test_module.ipynb          # 測試筆記本
│   └── test_module.py             # 對應 src/ 中模組的測試文件
│
├── .gitignore                     # Git 忽略項目
├── LICENSE                        # 項目的授權許可文件
├── README.md                      # 項目說明文件
├── requirements.txt               # 列出專案所需的Python庫和版本
└── setup.py                       # 專案的安裝腳本，定義專案的包信息和依賴關係
```

---

### Python_Project_template_lite

```
Project_template_lite/
├── config/                        # 用於存放系統設定檔
│   ├── config.yaml                # 專案的配置文件，使用YAML格式存放全局設定參數
│   ├── key.env                    # 金鑰
│   ├── logging.conf               # 日誌設定檔，配置Python的日誌記錄器
│   └── settings.ini               # 系統或應用層面的配置文件，使用INI格式存放設置項
│
├── docs/                          # 存放專案的相關文檔，如API說明、設計文檔等
│
├── envs/                          # 用於存放環境設定相關文件
│   └── environment.yml            # Conda環境的配置文件
│
├── src/                           # 存放專案的源代碼
│   ├── utils/                     # 存放常用的輔助函數或工具模組
│   │   └── __init__.py            # 使該目錄成為一個Python包
│   ├── __init__.py                # 使該目錄成為一個Python包
│   ├── main.py                    # 主程序入口，通常用於啟動應用
│   └── module.py                  # 各自實現不同功能的模組
│
├── tests/                         # 存放測試代碼
│   ├── __init__.py                # 使該目錄成為一個Python包
│   ├── test_module.ipynb          # 測試筆記本
│   └── test_module.py             # 對應 src/ 中模組的測試文件
│
├── .gitignore                     # Git 忽略項目
├── LICENSE                        # 項目的授權許可文件
├── README.md                      # 項目說明文件
└── requirements.txt               # 列出專案所需的Python庫和版本
```

---

### basic_frontend_project

```
basic_frontend_project/
├── docs/                          # 存放專案的相關文檔，如API說明、設計文檔等
│
├── public/                        # 靜態資源文件
│   ├── favicon.ico                # 網站圖標
│   └── robots.txt                 # 搜索引擎爬取規則
│
├── src/                           # 主程式碼
│   ├── assets/                    # 靜態資源 (圖片、字體、樣式等)
│   │   ├── fonts/                 # 字體文件
│   │   │   └── custom-font.ttf    # 示例字體
│   │   ├── images/                # 圖片資源
│   │   │   └── logo.png           # 示例圖片
│   │   └── styles/                # 樣式文件
│   │       ├── main.css           # 主 CSS 樣式
│   │       └── reset.css          # 樣式重置文件
│   │
│   ├── js/                        # JavaScript 文件
│   │   ├── app.js                 # 主應用程式邏輯
│   │   └── utils.js               # 工具函數
│   │
│   └── pages/                     # HTML 文件
│       ├── components/            # 可複用的 HTML 組件 (例如頁首、頁尾)
│       │   ├── footer.html        # 頁首組件
│       │   └── header.html        # 頁尾組件
│       └── index.html             # 網站主頁
│
├── tests/                         # 測試
│   └── test_1/                    # 測試 1
│       ├── test.css               # 測試 CSS 樣式
│       ├── test.html              # 測試 HTML 內容
│       └── test.js                # 測試 JS 效果
│
├── .gitignore                     # Git 忽略項目
├── LICENSE                        # 授權許可文件
└── README.md                      # 專案說明文件
```

---
