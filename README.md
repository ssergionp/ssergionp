<div align="center">

# Olá, eu sou o Sérgio 👋

**Servidor público migrando para desenvolvimento de software** — construindo projetos práticos de ponta a ponta, do código à produção, para consolidar fundamentos sólidos de back-end, front-end e sistemas distribuídos.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sergio-do-nascimento-pereira-7a174a112/)

</div>

🔭 **Atualmente estudando:** arquitetura de microsserviços, observabilidade
🌱 **Próximo passo:** Kubernetes, testes de carga mais avançados
💬 **Aberto a oportunidades** de estágio/júnior em desenvolvimento Java, Python ou full-stack
📫 **Como me encontrar:** [LinkedIn](https://www.linkedin.com/in/sergio-do-nascimento-pereira-7a174a112/)

---

## 🛠️ Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Projetos em destaque

### 📋 Task Manager — Full Stack (Auth + CRUD)

API REST com autenticação JWT, login social OAuth2 (Google), controle de acesso por role, testes automatizados e CI/CD — consumida por uma interface React com renovação automática de sessão. Os dois projetos estão publicados em produção, integrados um ao outro.

![Java](https://img.shields.io/badge/Java_25-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat-square&logo=google&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React_(Vite)-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

|            | Repositório                                                                 | Deploy                                                                        |
| ---------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 🔧 Backend  | [task-manager-api](https://github.com/ssergionp/task-manager-api)           | [API em produção](https://task-manager-api-vcu3.onrender.com/actuator/health) |
| 🎨 Frontend | [task-manager-frontend](https://github.com/ssergionp/task-manager-frontend) | [App em produção](https://task-manager-frontend-swart.vercel.app)             |

> ⚠️ Backend no plano gratuito do Render — a primeira requisição pode levar 30-50s enquanto o serviço "acorda".

**Destaques técnicos:**
- Autenticação JWT com access token + refresh token revogável
- Login social via Google (OAuth2), com vinculação automática de contas por e-mail
- Autorização por role (USER/ADMIN), com tratamento correto de 401 vs 403
- 21+ testes automatizados (unitários e de integração)
- Frontend com renovação automática e transparente de token expirado

<br>

### 📊 Customer Churn Predictor — Full Stack + Machine Learning

Aplicação que prevê churn de clientes usando Machine Learning (scikit-learn + SHAP), servida via API REST e visualizada em um dashboard React interativo, com histórico de previsões salvo em PostgreSQL.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-9C27B0?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(psycopg3)-336791?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React_(Vite)-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

|             | Repositório                                                     | Deploy                                                                |
| ----------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------ |
| 🐍 Backend   | [churn-predictor](https://github.com/ssergionp/churn-predictor) | [API em produção](https://churn-predictor-api-n7lu.onrender.com/docs) |
| ⚛️ Frontend | [churn-predictor](https://github.com/ssergionp/churn-predictor) | [App em produção](https://churn-predictor-lilac.vercel.app)           |

> ⚠️ Backend no plano gratuito do Render — a primeira requisição pode levar 30-50s enquanto o serviço "acorda".

**Destaques técnicos:**
- Explicabilidade por previsão via SHAP (não só importância global do modelo)
- Prompt/modelo treinado com dataset público real (Telco Customer Churn)
- Histórico completo de previsões persistido em banco relacional
- Deploy com backend (Render) e frontend (Vercel) desacoplados, com CORS configurado via variável de ambiente

<br>

### 🚗 FIPE Explorer — Full Stack (Análise de Dados)

Ferramenta full-stack para buscar, comparar e analisar preços de veículos da Tabela FIPE: busca com filtros combináveis, curva de depreciação por modelo, comparador lado a lado e rankings de marcas por preço médio — construída sobre a importação e normalização de mais de 50 mil registros reais.

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React_(Vite)-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

|                | Repositório                                                  | Descrição                                                                                          |
| -------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| 🚗 Full Stack   | [fipe-explorer](https://github.com/ssergionp/fipe-explorer)   | Busca, curva de depreciação, comparador e rankings sobre +50 mil registros reais da Tabela FIPE      |

**Destaques técnicos:**
- Import e normalização de +50 mil registros reais da Tabela FIPE num schema relacional (marca, modelo, ano, combustível, preço)
- Curva de depreciação por modelo com Recharts, tratando corretamente o caso "Zero KM" (eixo categórico, sem distorcer escala) e múltiplos combustíveis no mesmo ano
- Cálculo de preço médio por marca com correção de viés estatístico: usa o ano mais recente de cada modelo em vez do histórico inteiro, evitando que marcas com mais anos catalogados dominem o ranking
- Filtros de busca e seleção de comparação refletidos na URL, permitindo compartilhar links de busca e de comparação diretamente

<br>

### 🔗 URL Shortener — System Design (Rate Limiting + Caching)

Encurtador de URLs focado em conceitos de system design: rate limiting (Redis, fixed-window), cache-aside pattern, e testes de carga documentados com k6 (~396 req/s, p95 de 22ms sob carga sustentada).

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=testcontainers&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

|          | Repositório                                                | Descrição                                            |
| -------- | ------------------------------------------------------------- | ------------------------------------------------------- |
| ☕ Backend | [url-shortener](https://github.com/ssergionp/url-shortener) | Rate limiting, cache-aside, testes de carga documentados |

**Destaques técnicos:**
- Rate limiting por IP via Redis (fixed-window counter), com header `Retry-After`
- Cache-aside pattern: leituras servidas pelo Redis, com fallback e repopulação automática no PostgreSQL
- Testes de carga com k6: comparação entre tráfego limitado (rate limiter ativo) e capacidade real do sistema
- Testes de integração com Testcontainers (PostgreSQL real via Docker)

<br>

### 🤖 RAG Legislation Assistant — IA Generativa (Spring AI + Claude)

Chatbot com Retrieval-Augmented Generation (RAG) que responde perguntas sobre normas públicas com base estritamente nos documentos indexados — não no conhecimento geral do modelo. Pipeline completo: ingestão → chunking → embeddings locais (ONNX) → busca vetorial (pgvector) → geração com Claude, com citação das fontes usadas em cada resposta.

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-D97757?style=flat-square&logo=anthropic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

|          | Repositório                                                                        | Descrição                                       |
| -------- | -------------------------------------------------------------------------------------- | -------------------------------------------------- |
| ☕ Backend | [rag-legislation-assistant](https://github.com/ssergionp/rag-legislation-assistant) | Pipeline RAG completo com Spring AI + Claude       |

**Destaques técnicos:**
- Pipeline RAG completo (retrieval → augmentation → generation) com Spring AI
- Prompt de sistema rígido: o modelo se recusa a responder fora do contexto recuperado, evitando alucinação
- Embeddings gerados localmente (sem custo de API); só a geração final usa a API do Claude
- Transparência: cada resposta exibe os trechos-fonte usados para gerá-la

<br>

### 🧩 Microservices Task Platform — Distributed Systems (5 serviços)

Domínio de gerenciamento de tarefas dividido em 5 microsserviços independentes: descoberta de serviços (Eureka), API Gateway único, comunicação síncrona resiliente (circuit breaker + retry) e mensageria assíncrona (RabbitMQ). Testado inclusive derrubando um serviço em produção para validar o fallback do circuit breaker.

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud_(Eureka_%2B_Gateway)-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-FF4088?style=flat-square)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(per_service)-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

|              | Repositório                                                                          | Descrição                                              |
| ------------ | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| ☕ Plataforma | [microservices-task-platform](https://github.com/ssergionp/microservices-task-platform) | 5 serviços: Eureka, Gateway, Users, Tasks, Notifications |

**Destaques técnicos:**
- Descoberta de serviços com Eureka + roteamento dinâmico via API Gateway (`lb://service-name`)
- Chamada síncrona com circuit breaker + retry (Resilience4j): falha graciosamente com fallback em vez de propagar erro
- Mensageria assíncrona com RabbitMQ: eventos consumidos de forma totalmente desacoplada
- Database per service: cada serviço com seu próprio PostgreSQL, sem acoplamento direto de schema

---

## 📊 GitHub Stats

<div align="center">

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=ssergionp&show_icons=true&theme=default)
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=ssergionp&layout=compact)

</div>
