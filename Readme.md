Hi, I'm Mohit Nadipineni

Generative AI & full-stack developer. I build AI applications with Python and JavaScript: retrieval-augmented generation (RAG), agentic workflows, automation pipelines and web apps, with a focus on reliable, well-tested systems.

Oracle Certified Professional, Java SE 8 · Postgraduate in Mobile Application Design and Development (Lambton College)

Featured project: Hybrid RAG Finance Chatbot

A backend that answers finance, tax and banking questions from a company's documents and its database, and cites the source of every fact ([D1] for a document, [S1] for a database query).

Hybrid search: keyword and vector search merged with Reciprocal Rank Fusion, with per-document permissions. Found the right document for 6/6 test questions.
Safe AI-written SQL: three independent locks (a sqlglot guard, a read-only database user and a read-only transaction). Blocks 15 attack patterns in tests.
Agentic workflow: a LangGraph agent routes each question to documents, the database, or both, then checks its own citations.
API: FastAPI with conversations, follow-up memory, streaming (SSE), feedback and API-key logins; users only ever see their own data.
Quality: 57 automated tests, including dedicated safety tests, plus an evaluation harness over 16 golden questions.
Runs anywhere: Docker Compose starts the database and the app with one command.

Python · FastAPI · LangGraph · LangChain · PostgreSQL · pgvector · sqlglot · Docker · pytest

Status: fully built and tested; currently being connected to Azure OpenAI.

Other recent work

Career Orchestrator OS · n8n · Python · Generative AI An automation platform for the job-search lifecycle: job discovery, AI parsing of job descriptions into structured role and skill data, tailored outreach, and application tracking, built as modular, re-runnable n8n workflows with embedded Python steps.

E-commerce fashion storefront · JavaScript A full-featured retail web app modelled on leading fashion platforms: component architecture, routing between storefront views, state management and rendering performance.

Local AI development environment · Ollama · Cursor · qwen3-coder:30b A private, on-device AI coding setup: Ollama serving a 30B-parameter code model to the Cursor editor, so source code and prompts never leave the machine.

Corporate website renovation · Git · GitHub Redesigned and restructured a company website, cleaned up its repository structure, and owned the production launch through GitHub.

Skills
Languages: Python, Java (OCP certified), JavaScript, SQL, HTML/CSS
Generative & agentic AI: RAG, LangGraph agents, LangChain, prompt engineering, embeddings and vector search, local LLMs with Ollama
Backend & data: FastAPI, pydantic, PostgreSQL, pgvector, full-text search
Automation: n8n workflows with Python
Frontend & mobile: JavaScript web apps (routing, state management); mobile application design and development
Tools: Docker, Docker Compose, Git & GitHub, pytest, Cursor
Experience
Full-stack & Generative AI Developer, self-employed · 2026 – present
Junior Programmer, Aroha Technologies · Hyderabad · 2019 – 2020
Education & certifications
Postgraduate studies, Mobile Application Design and Development, Lambton College, Toronto · 2021 – 2022
Bachelor's, Electronics and Communication Engineering, JNTUH · 2015 – 2019
Oracle Certified Professional, Java SE 8 Programmer
Oracle Certified Associate, Java SE 8 Programmer
Contact

LinkedIn · m304n202@gmail.com
