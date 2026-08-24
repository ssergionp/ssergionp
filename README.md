### 🚀 Projetos em destaque

#### 📋 Task Manager — Full Stack (Backend + Frontend)

API REST em Java + Spring Boot com autenticação JWT, login social OAuth2 (Google), controle de acesso por role, testes automatizados e CI/CD — consumida por uma interface React com renovação automática de sessão. Os dois projetos estão publicados em produção, integrados um ao outro.

|            | Repositório                                                                 | Descrição                                                                                  | Deploy                                                                        |
| ---------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
| 🔧 Backend  | [task-manager-api](https://github.com/ssergionp/task-manager-api)           | Java 25, Spring Boot 4.1, Spring Security, JWT, OAuth2, PostgreSQL, Docker, GitHub Actions | [API em produção](https://task-manager-api-vcu3.onrender.com/actuator/health) |
| 🎨 Frontend | [task-manager-frontend](https://github.com/ssergionp/task-manager-frontend) | React (Vite), React Router, Axios, Tailwind CSS v4                                         | [App em produção](https://task-manager-frontend-swart.vercel.app)             |

> ⚠️ O backend está hospedado no plano gratuito do Render — a primeira requisição pode levar de 30 a 50 segundos enquanto o serviço "acorda" após período de inatividade.

**Destaques técnicos:**

- Autenticação JWT com access token + refresh token revogável
- Login social via Google (OAuth2), com vinculação automática de contas por e-mail
- Autorização por role (USER/ADMIN), com tratamento correto de 401 vs 403
- 21+ testes automatizados (unitários e de integração)
- CI/CD via GitHub Actions
- Frontend com renovação automática e transparente de token expirado

---

#### 📊 Customer Churn Predictor — Full Stack + Machine Learning

Aplicação full-stack que prevê churn de clientes usando um modelo de Machine Learning (scikit-learn + SHAP), servido via API REST e visualizado em um dashboard React interativo com histórico de previsões salvo em PostgreSQL.

|             | Repositório                                                     | Descrição                                                                          | Deploy                                                                |
| ----------- | --------------------------------------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| 🐍 Backend   | [churn-predictor](https://github.com/ssergionp/churn-predictor) | Python, FastAPI, scikit-learn, SHAP, PostgreSQL (psycopg3), Docker, GitHub Actions | [API em produção](https://churn-predictor-api-n7lu.onrender.com/docs) |
| ⚛️ Frontend | [churn-predictor](https://github.com/ssergionp/churn-predictor) | React (Vite), TypeScript, Recharts                                                 | [App em produção](https://churn-predictor-lilac.vercel.app)           |

> ⚠️ O backend está hospedado no plano gratuito do Render — a primeira requisição pode levar de 30 a 50 segundos enquanto o serviço "acorda" após período de inatividade.

---

#### 🔗 URL Shortener — System Design (Rate Limiting + Caching)

Encurtador de URLs em Java + Spring Boot focado em conceitos de system design: rate limiting (Redis, fixed-window), cache-aside pattern, e testes de carga documentados com k6 (~396 req/s, p95 de 22ms sob carga sustentada).

|          | Repositório                                                | Descrição                                                                             |
| -------- | ----------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| ☕ Backend | [url-shortener](https://github.com/ssergionp/url-shortener) | Java 21, Spring Boot 3, Redis, PostgreSQL, Testcontainers, k6, Docker, GitHub Actions |

**Destaques técnicos:**

- Rate limiting por IP via Redis (fixed-window counter), com header `Retry-After`
- Cache-aside pattern: leituras servidas pelo Redis, com fallback e repopulação automática no PostgreSQL
- Testes de carga com k6 documentados no README: comparação entre tráfego limitado (rate limiter ativo) e capacidade real do sistema (~396 req/s, 0% de falha)
- Testes de integração com Testcontainers (PostgreSQL real via Docker)

---

#### 🤖 RAG Legislation Assistant — IA Generativa (Spring AI + Claude)

Chatbot com Retrieval-Augmented Generation (RAG) que responde perguntas sobre normas públicas com base estritamente nos documentos indexados — não no conhecimento geral do modelo. Pipeline completo: ingestão → chunking → embeddings locais (ONNX) → busca vetorial (pgvector) → geração com Claude, com citação das fontes usadas em cada resposta.

|          | Repositório                                                                        | Descrição                                                                                |
| -------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| ☕ Backend | [rag-legislation-assistant](https://github.com/ssergionp/rag-legislation-assistant) | Java 21, Spring Boot, Spring AI, Claude (Anthropic), PostgreSQL + pgvector, embeddings locais (ONNX) |

**Destaques técnicos:**

- Pipeline RAG completo (retrieval → augmentation → generation) com Spring AI
- Prompt de sistema rígido: o modelo se recusa a responder fora do contexto recuperado, evitando alucinação
- Embeddings gerados localmente (sem custo de API), só a geração final usa a API do Claude
- Transparência: cada resposta exibe os trechos-fonte usados para gerá-la

  ### 🧩 Microservices Task Platform — Distributed Systems (5 serviços)

Domínio de gerenciamento de tarefas dividido em 5 microsserviços independentes: descoberta de serviços (Eureka), API Gateway único, comunicação síncrona resiliente (circuit breaker + retry) e mensageria assíncrona (RabbitMQ). Testado inclusive derrubando um serviço em produção para validar o fallback do circuit breaker.

| | Repositório | Descrição |
|---|---|---|
| ☕ Plataforma | [microservices-task-platform](https://github.com/ssergionp/microservices-task-platform) | Java 21, Spring Boot, Spring Cloud (Eureka, Gateway, LoadBalancer), Resilience4j, RabbitMQ, PostgreSQL (database-per-service), Docker Compose, GitHub Actions |

**Destaques técnicos:**
- Descoberta de serviços com Eureka + roteamento dinâmico via API Gateway (`lb://service-name`)
- Chamada síncrona entre serviços com circuit breaker + retry (Resilience4j): falha graciosamente com fallback em vez de propagar erro quando uma dependência cai
- Mensageria assíncrona com RabbitMQ: eventos de "tarefa criada" consumidos de forma totalmente desacoplada
- Database per service: cada serviço tem seu próprio PostgreSQL, sem acoplamento direto de schema

### 📊 GitHub Stats

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=ssergionp&show_icons=true&theme=default)
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=ssergionp&layout=compact)
