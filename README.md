# AI products

A short overview of AI applications I've worked on at ACI Limited's AI team. The source code is private, so this page covers what each product does, what I built and the stack.

## ShoktiAI

AI tutoring and mock-test platform. Live at [shokti.ai](https://www.shokti.ai/).

- Refactored the backend from raw queries to an ORM-based structure.
- Containerized the platform and deployed it to production.
- Stack: React, Node.js, PostgreSQL, Docker.

## AgroGPT

Agricultural AI assistant. Live at [agrogpt.app](https://www.agrogpt.app/).

- Fixed deployment issues and merged two weather services into one API.
- Moved login from JWT to Google OAuth.
- Stack: Node.js, React, Docker.

## Othe

Multi-tenant AI agent marketplace, in beta at [othe.app](https://othe.app/). Designed to scale to 1000+ agents.

- Designed the architecture and the data model, with tenant-scoped multi-tenancy.
- Wrote the delivery roadmap.
- Stack: PostgreSQL, JWT, Claude Batches API.

## AgentMD

Internal RAG knowledge assistant with document chat and schedule sync. Used daily by the client team.

- Built the RAG pipeline, background indexing, Google Drive sync and login.
- Stack: Node.js, React, FastAPI, ChromaDB, OAuth 2.0.

## Public repositories

- [aci-chimera-01](https://github.com/aliarman1/aci-chimera-01): multimodal chat app on Gemini (Next.js, FastAPI).
- [aci-ai-case-study](https://github.com/aliarman1/aci-ai-case-study): YOLO object detection with Gemini Q&A (Docker, JWT).

## Contact

[aliarman.dev](https://www.aliarman.dev/) · [LinkedIn](https://www.linkedin.com/in/aliarman1/)
