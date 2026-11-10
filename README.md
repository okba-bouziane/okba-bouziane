# Okba Bouziane

Full-Stack & AI Engineer in Algiers. 6 years building web and mobile products with Angular, React, TypeScript and NestJS, and an MSc in Artificial Intelligence.

I build AI agents and RAG systems inside real products, with the same auth, tests and evals as the rest of the app.

**Portfolio:** [devokba.vercel.app](https://devokba.vercel.app) · **LinkedIn:** [okba-bouziane](https://www.linkedin.com/in/okba-bouziane/) · **Email:** okba.bouziane@outlook.com

## Projects

| Project | What it does | Proof |
|---|---|---|
| [Secure Agent Workspace](https://github.com/okba-bouziane/SecureAgentWorkspace) | An AI agent that acts with the signed-in user's own Keycloak permissions. Every write waits for human approval. | 90 automated tests · recall@3 1.00 on 18 questions · 10/10 injection attacks detected |
| [VoiceDesk](https://github.com/okba-bouziane/VoiceDesk) | A voice receptionist that books appointments by voice (LiveKit, LangGraph, gRPC). [Live demo](https://voicedesk-beta.vercel.app) | 106 pytest tests · 1.59 s speech-to-reply on a live call |
| [OpsGraph](https://github.com/okba-bouziane/OpsGraph) | Graph RAG on Neo4j for on-call engineers: who to page, what breaks, which runbook applies. | multi-hop full coverage 0.43 → 0.78 vs vector search · 49 pytest tests |
| [SecureMCP](https://github.com/okba-bouziane/SecureMCP) | An MCP server where every agent tool call is checked against a Keycloak JWT and audited. | role-gated tools · every allowed or denied call audited |
| [UniPath](https://github.com/okba-bouziane/UniPath) | A RAG admissions assistant that cites a source on every answer. [Live demo](https://unipath-okba.streamlit.app) | 10/10 on the answer eval |
| [nest-clean-architecture](https://github.com/okba-bouziane/nest-clean-architecture) | NestJS clean architecture with PostgreSQL, MongoDB, Keycloak and an Angular client. | framework-free domain layer · unit tests in CI |

## Stack

**AI:** LangGraph, LangChain, LlamaIndex, RAG, Graph RAG, MCP, pgvector, evals
**Frontend:** Angular, React, TypeScript, RxJS, React Native
**Backend:** Node.js, NestJS, Python, FastAPI, REST, GraphQL, gRPC
**Data and security:** PostgreSQL, MongoDB, Neo4j, Redis, Keycloak, OAuth2 / OpenID Connect, Docker, CI/CD
