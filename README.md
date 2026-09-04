嗨，我是一名全端工程師，具備近 4 年 Web 開發經驗，主要優勢是前端架構與產品介面開發，同時具備 RESTful API、資料庫設計、權限整合及部署能力。

主要使用 Vue、Nuxt、React、Next.js 與 TypeScript，曾參與多項 B2B／B2C 商業專案的開發與正式交付，涵蓋企業管理平台、電商、NFC、eSIM 與品牌官網。

後端與資料層主要使用 Python、FastAPI、PostgreSQL、Supabase 與 Docker。目前也投入 AI Agent、RAG 與開發流程自動化，關注如何透過來源驗證、自動測試、模型評估及人工審核，建立可驗證、可追蹤且能由人控制的 AI 產品流程。

## Featured Projects

### Notion GitHub Coding Agent

以人工審核為核心的 AI 軟體工程工作平台，整合 Notion 任務、GitHub Issues、AI Patch 與模型評估流程。

- 整合 Notion API、GitHub API 與 Webhook，處理任務、Issue、Pull Request 狀態及失敗重試
- 使用隔離的 Git worktree 執行 baseline checks、程式碼檢索、Patch 產生與自動測試
- 設計 Evidence Gate，驗證模型引用的檔案、行號與原始內容
- 實作人工核准與 base SHA 檢查，避免 AI 未經授權推送或覆蓋過期程式碼
- 建立 Exact Replay、hidden acceptance checks 與 regression gate，比較模型、Prompt 及 Retrieval 策略
- 使用 Next.js、TypeScript、Python、Supabase、OpenAI API、Notion API 與 GitHub API 開發

[Live Demo](https://notion-github-coding-agent.vercel.app) ·
[Demo Video](https://youtu.be/TPr4YH-15n8) ·
[Repository](https://github.com/c-y-s-s/notion-github-coding-agent)

---

### Restaurant Operations RAG

具備來源引用與分店資料隔離的餐廳營運知識助理，協助使用者查詢菜單、食品安全、設備操作及分店 SOP。

- 使用 FastAPI 與 Pydantic 建立文件處理、檢索及問答 API
- 使用 PostgreSQL、Supabase 與 pgvector 儲存文件、權限及向量資料
- 結合關鍵字與向量檢索，建立 Hybrid Search 流程
- 實作來源引用驗證與拒答機制，降低無法驗證的模型輸出
- 建立測試資料集與量化評估流程，比較不同檢索策略及回答品質
- 使用 Nuxt 3、Vue 3、TypeScript、FastAPI、PostgreSQL、pgvector、OpenAI API 與 Docker 開發

[Live Demo](https://restaurant-operations-rag.vercel.app) ·
[Repository](https://github.com/c-y-s-s/restaurant-operations-rag)

## Tech Stack

- **Frontend:** TypeScript、Vue、Nuxt、React、Next.js、Pinia、Redux Toolkit
- **Backend:** Python、FastAPI、Node.js、RESTful API、Pydantic
- **Database:** PostgreSQL、Supabase、pgvector
- **AI Application:** OpenAI API、Structured Outputs、Tool Calling、RAG、Embeddings
- **Workflow:** GitHub API、Notion API、Webhooks、Git Worktrees、Human-in-the-loop
- **Testing & Delivery:** Vitest、Jest、Pytest、Docker、Vercel、Render

## Current Focus

- Full-stack product development
- Reliable AI agents and RAG systems
- Evaluation, source validation and human review
- Developer workflow automation
