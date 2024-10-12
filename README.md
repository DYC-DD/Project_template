# Project_template

##### Project 資料夾範本

---

### 專案資料夾 開發結構樹狀圖
```
my_python_project/
│
├── README.md  # 專案說明文件
├── LICENSE  # 授權文件
├── setup.py  # 安裝配置文件
├── requirements.txt  # 依賴包列表
├── .gitignore  # Git 忽略文件列表
├── .env  # 環境變數文件
├── .flake8  # Flake8 配置文件
├── .pre-commit-config.yaml  # 預提交鉤子配置文件
├── src/  # 源碼目錄
│   ├── __init__.py  # 包初始化文件
│   ├── main.py  # 主程式文件
│   ├── module1.py  # 模組1
│   ├── module2.py  # 模組2
│   └── utils/  # 工具目錄
│       ├── __init__.py  # 包初始化文件
│       └── helper.py  # 助手函數
├── tests/  # 測試目錄
│   ├── __init__.py  # 包初始化文件
│   ├── test_module1.py  # 模組1 測試文件
│   └── test_module2.py  # 模組2 測試文件
├── docs/  # 文件目錄
│   └── project_documentation.md  # 專案文檔
├── data/  # 數據目錄
│   ├── raw/  # 原始數據
│   │   └── data.csv  # 原始數據文件
│   └── processed/  # 處理後數據
│       └── processed_data.csv  # 處理後數據文件
├── notebooks/  # Jupyter 筆記本
│   └── exploration.ipynb  # 探索性分析筆記本
├── envs/  # 環境配置
│   ├── environment.yml  # 環境配置文件
│   └── Dockerfile  # Docker 配置文件
└── config/  # 配置目錄
    ├── config.yaml  # 配置文件 (YAML 格式)
    ├── settings.ini  # 設定文件 (INI 格式)
    └── logging.conf  # 日誌配置文件
```
---
### 專案資料夾 開發結構詳解
1. `README.md`: 項目說明文件，簡要介紹專案的目標、使用方法和主要功能。
2. `LICENSE`: 項目的授權許可文件，指定專案的版權資訊。
3. `setup.py`: 專案的安裝腳本，定義專案的包信息和依賴關係，使用 pip 安裝時非常有用。
4. r`equirements.txt`: 列出專案所需的Python庫和版本，通過 pip install -r requirements.txt 可以快速安裝依賴項。
5. `.gitignore`: 指定哪些文件和資料夾不應該被Git版本控制系統追蹤（如虛擬環境文件、編譯生成的文件等）。
6. `.env`: 環境變數設定文件，存放敏感數據（如API密鑰、密碼等），不應該上傳到版本控制系統中。可以使用 python-dotenv 來加載這些環境變數。
7. `.flake8`: Flake8 設定檔，用於配置代碼風格檢查的規則。
8. `.pre-commit-config.yaml`: Pre-commit 設定檔，用於設定Git提交前的自動檢查任務，如代碼格式化、風格檢查等。
9. `src/`: 存放專案的源代碼。建議將代碼模組化，並保持每個模塊的職責單一。 
    1. **`init**.py`: 使該目錄成為一個Python包。 
    2. `main.py`: 主程序入口，通常用於啟動應用。 
    3. `module1.py, module2.py`: 各自實現不同功能的模組。 
    4. `utils/`: 存放常用的輔助函數或工具模組。
10. `tests/`: 存放測試代碼，使用 unittest 或 pytest 等測試框架撰寫。 
    1. `init.py`: 使測試目錄成為一個Python包。 
    2. `test_module1.py, test_module2.py`: 對應 src/ 中模組的測試文件。
11. `docs/`: 存放專案的相關文檔，如API說明、設計文檔等。
12. `data/`: 存放專案所需的數據集。 
    1. `raw/`: 原始數據文件。
        1. `processed/`: 處理過的數據文件。
13. `notebooks/`: 存放Jupyter Notebook文件，適合用於數據分析、模型訓練等。
14. `envs/`: 用於存放環境設定相關文件。 
    1. `environment.yml`: Conda 環境的配置文件，列出專案依賴項，可使用 conda env create -f environment.yml 來建立環境。 
    2. `Dockerfile`: 用於建立Docker容器的設定檔，方便專案的容器化部署。
15. `config/`: 用於存放系統設定檔。 
    1. `config.yaml`: 專案的配置文件，使用YAML格式存放全局設定參數。 
    2. `settings.ini`: 系統或應用層面的配置文件，使用INI格式存放設置項。 
    3. `logging.conf`: 日誌設定檔，配置Python的日誌記錄器。
