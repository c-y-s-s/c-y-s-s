# Hi, I'm Leo 👋

I'm a frontend-focused developer building practical web applications with React, Next.js, Vue, Nuxt, and TypeScript.

I care about maintainable UI architecture, reliable API integration, and turning unclear product requirements into usable engineering workflows.

Recently, I have been exploring how AI agents can improve developer productivity—not just through chat, but through structured workflows with tool usage, source citations, and human approval.

## 🚀 Featured Projects

### Frontend Agent Workspace

An AI-powered developer workspace that helps frontend engineers investigate requirements, APIs, bugs, and pull requests.

Built with Next.js, TypeScript, Python, FastAPI, PostgreSQL, OpenAI, and the GitHub API.

#### Agent capabilities

- **Task Investigator** — Converts a GitHub Issue into a cited implementation plan
- **API Analyzer** — Analyzes Response JSON and OpenAPI documents for frontend integration
- **Bug Investigator** — Uses error context and repository evidence to generate ranked hypotheses
- **Code Review Agent** — Reviews bounded pull request changes and reports evidence-based risks
- **Human-in-the-loop approval** — Requires engineers to approve or reject Agent output
- **Replay Mode** — Provides a stable demonstration without external API dependencies

#### Engineering highlights

- Built structured Agent workflows with controlled, read-only tools
- Integrated GitHub Issues, repository files, pull requests, and CI evidence
- Streamed workflow progress through Server-Sent Events
- Added structured AI output validation with Pydantic
- Implemented citations, rate limits, token tracking, and repository allowlists
- Tested Agent workflows using mocked GitHub and OpenAI providers
- Deployed Next.js on Vercel and FastAPI with PostgreSQL on Render

🔗 Live Demo: https://frontend-task-investigator.vercel.app  
📦 Repository: https://github.com/c-y-s-s/frontend-task-investigator

---

### Restaurant Operations RAG

A citation-first AI assistant for restaurant operations, built with OpenAI, FastAPI, Nuxt 3, Supabase PostgreSQL, and pgvector.

- Built a RAG workflow with embeddings and vector search
- Developed backend APIs with FastAPI
- Implemented citation-backed answers
- Built the frontend with Nuxt 3
- Deployed a live demo on Vercel

🔗 Live Demo: https://restaurant-operations-rag.vercel.app  
📦 Repository: https://github.com/c-y-s-s/restaurant-operations-rag

## 🛠 Tech Stack

**Frontend:** HTML, CSS, RWD, JavaScript, TypeScript, React, Next.js, Vue, Nuxt  
**State & UI:** Redux Toolkit, Vuex, Pinia, styled-components, Vuetify, Element Plus  
**Backend:** Python, FastAPI, Node.js, Express, RESTful APIs  
**Database:** PostgreSQL, MySQL, MongoDB, Supabase, pgvector  
**AI & Agents:** OpenAI API, structured output, tool calling, RAG, embeddings, human-in-the-loop workflows  
**Testing & Tools:** Vitest, Jest, Selenium, Pytest, Git, GitHub, GitLab, Postman, Figma  
**Deployment:** Docker, Docker Compose, Vercel, Render, Firebase, AWS basics
