# Hi there 👋

嗨，我是一名前端開發工程師，主要使用 React、Next.js、Vue、Nuxt 與 TypeScript，打造具備清楚架構且容易維護的 Web 應用程式。

除了前端開發，我也持續探索 AI Agent、RAG 與開發流程自動化，包含 API 整合、結構化輸出、工具使用、來源驗證、人工審核及模型評估。

我關注的不只是讓模型產生答案，而是如何把 AI 能力轉化為可驗證、可追蹤且能由人控制的實際產品流程。

## 精選專案

### Notion GitHub Coding Agent

一套以人工審核為核心的 AI 軟體工程工作平台，整合 Notion 任務、GitHub Issues、AI Patch 與模型評估流程。

- 整合 Notion 與 GitHub Webhook，處理內部任務、外部 Issue、PR 狀態與失敗重試
- 使用隔離的 Git worktree 執行 baseline checks、程式碼檢索、Patch 產生與測試
- 設計 Evidence Gate，驗證模型引用的檔案、行號與原始內容
- AI 只能準備 Patch；必須經過人工核准及 base SHA 檢查後才能推送分支
- 建立 Exact Replay、hidden acceptance checks 與 regression gate，比較模型、Prompt 和 Retrieval 策略
- 使用 Next.js、TypeScript、Python、Supabase、OpenAI API、Notion API 與 GitHub API 開發

[Live Demo](https://notion-github-coding-agent.vercel.app) ·
[Demo Video](https://youtu.be/TPr4YH-15n8) ·
[Repository](https://github.com/c-y-s-s/notion-github-coding-agent)

### Restaurant Operations RAG

一套以來源引用為核心的餐廳營運知識檢索助理，協助使用者從內部知識中取得可追溯的回答。

- 建立文件處理、Embedding、向量搜尋與答案生成流程
- 使用 pgvector 儲存及檢索語意向量
- 在回答中保留來源引用，降低無法驗證的模型輸出
- 使用 Nuxt 3、FastAPI、OpenAI、Supabase 與 pgvector 開發

[Live Demo](https://restaurant-operations-rag.vercel.app) ·
[Repository](https://github.com/c-y-s-s/restaurant-operations-rag)

## 🛠 技術能力

- **前端：** TypeScript、React、Next.js、Vue、Nuxt
- **後端與資料：** Python、FastAPI、Node.js、PostgreSQL、Supabase
- **AI 與 Agent：** OpenAI API、Structured Outputs、Tool Calling、RAG、Embeddings、Human-in-the-loop Workflows
- **整合與工作流：** GitHub API、Notion API、Webhooks、Git Worktrees
- **測試與部署：** Vitest、Jest、Pytest、Docker、Vercel、Render
