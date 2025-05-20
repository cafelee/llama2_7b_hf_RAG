🦙 LLaMA.cpp API & UI
本專案是基於 llama.cpp 打包的本地 LLM API + UI，可讓他人無需設定本地環境即可使用你的模型。

🔧 安裝步驟
請依照以下步驟完成環境安裝與啟動：

1. 建立 Conda 環境

conda env create -f environment.yml
conda activate llama_cpp

2. 安裝 Python 套件

pip install -r requirements.txt

3. 執行主程式

python main.py

📁 專案結構（建議補充）
├── main.py                # 主程式進入點
├── environment.yml        # Conda 環境依賴
├── requirements.txt       # Pip 套件依賴
├── ...
*faiss_index, mistral-7b-instruct-v0.2.Q4_K_M.gguf檔案過大，未上傳，請用googledrive下載

🚀 功能簡介（建議補充）
本地推論（LLaMA 模型）

API 介面（可供串接）

Web UI（使用者介面）

💬 聯絡方式
如有任何問題，歡迎開 issue 或聯絡我 🙌
