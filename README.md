### 01 / AI 應用工程（LLM Agent／RAG）

| 專案 | 做什麼 | 技術重點 |
|---|---|---|
| [**citeguard-energy**](https://github.com/ck-x-x/citeguard-energy) | 能源／資料中心液冷文獻調研，報告每句附證據編號，自動剔除捏造引用 | **Dify Workflow**（知識庫＋FastAPI→OpenAlex 平行檢索）、Code 節點引用白名單校驗、Workflow API 自動評測（124 引用 100% 有效、陷阱題 3/3 拒答） |
| [**financial-report-agent**](https://github.com/ck-x-x/financial-report-agent) | 用中文問美股財報，回答附 SEC 原文連結 | Tool Use Agent、Python 白名單派送、數字查核防幻覺、Groq／Gemini 自動切換 |
| [**elon-musk-rag-chatbot**](https://github.com/ck-x-x/elon-musk-rag-chatbot) | 繁中知識庫問答聊天機器人 | 依 Markdown 標題切塊、FAISS 向量＋關鍵字混合檢索、安全邊界、自動化測試 |

### 02 / 知識庫整理

| 專案 | 做什麼 | 技術重點 |
|---|---|---|
| [**energy-power-llm-wiki**](https://github.com/ck-x-x/energy-power-llm-wiki) | 能源與電力技術知識庫（儲能、氫能、Power-to-Gas、天然氣水合物）＋教學簡報 | Quartz v4、GitHub Pages 自動部署 · [網站](https://ck-x-x.github.io/energy-power-llm-wiki/) |

### 03 / 互動網頁

| 專案 | 做什麼 | 技術重點 |
|---|---|---|
| [**xinliu-bjj**](https://github.com/ck-x-x/xinliu-bjj) | 巴西柔術互動戰術路徑圖，86 項技術、五大賽事規則查詢 | 先寫規格書再實作、單一 HTML 檔 · [線上試用](https://ck-x-x.github.io/xinliu-bjj/) |
| [**midnight-diner-atlas**](https://github.com/ck-x-x/midnight-diner-atlas) | 《深夜食堂》料理圖鑑，依部數／類型篩選 | 統一版型、可持續擴充的內容網站 · [網站](https://ck-x-x.github.io/midnight-diner-atlas/) |

### 04 / 創作工具箱

| 類別 | 工具 | 主要用途 |
| :--- | :--- | :--- |
| **模型與推論** | `Gemini` `Groq` `Ollama` | 雲端 API 與本地端 LLM 推論 |
| **AI 應用與檢索** | `Dify` `LangChain` `FAISS` | Agent 工作流編排與向量檢索（RAG） |
| **後端與介面** | `FastAPI` `Gradio` | API 服務開發與快速 AI Demo 介面 |
| **語言與前端** | `Python` `HTML／JavaScript` | 核心開發與輕量網頁互動 |
| **環境與部署** | `Docker` `Google Colab` `GitHub Pages` | 容器化打包、雲端實驗與靜態網站託管 |
