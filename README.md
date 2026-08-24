### Olá, eu sou o Sérgio 👋

Servidor público migrando para a área de desenvolvimento, construindo projetos práticos de ponta a ponta — do código à produção — para consolidar fundamentos sólidos de back-end e front-end.

🔭 Atualmente estudando: **Spring AI**, testes de carga
🌱 Próximo passo: projeto com IA generativa usando Spring AI, depois arquitetura de microsserviços
💬 Aberto a oportunidades de estágio/júnior em desenvolvimento Java ou full-stack
📫 Como me encontrar: [LinkedIn](https://www.linkedin.com/in/sergio-do-nascimento-pereira-7a174a112/)

---

### 🛠️ Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 🚀 Projetos em destaque

#### 📋 Task Manager — Full Stack (Backend + Frontend)

API REST em Java + Spring Boot com autenticação JWT, login social OAuth2 (Google), controle de acesso por role, testes automatizados e CI/CD — consumida por uma interface React com renovação automática de sessão. Os dois projetos estão publicados em produção, integrados um ao outro.

| | Repositório | Descrição | Deploy |
|---|---|---|---|
| 🔧 Backend | [task-manager-api](https://github.com/ssergionp/task-manager-api) | Java 25, Spring Boot 4.1, Spring Security, JWT, OAuth2, PostgreSQL, Docker, GitHub Actions | [API em produção](https://task-manager-api-vcu3.onrender.com/actuator/health) |
| 🎨 Frontend | [task-manager-frontend](https://github.com/ssergionp/task-manager-frontend) | React (Vite), React Router, Axios, Tailwind CSS v4 | [App em produção](https://task-manager-frontend-swart.vercel.app) |

> ⚠️ O backend está hospedado no plano gratuito do Render — a primeira requisição pode levar de 30 a 50 segundos enquanto o serviço "acorda" após período de inatividade.

### 📊 Customer Churn Predictor — Full Stack + Machine Learning

Aplicação full-stack que prevê churn de clientes usando um modelo de Machine Learning (scikit-learn + SHAP), servido via API REST e visualizado em um dashboard React interativo com histórico de previsões salvo em PostgreSQL.

| | Repositório | Descrição | Deploy |
|---|---|---|---|
| 🐍 Backend | [churn-predictor](https://github.com/ssergionp/churn-predictor) | Python, FastAPI, scikit-learn, SHAP, PostgreSQL (psycopg3), Docker, GitHub Actions | [API em produção](https://churn-predictor-api-n7lu.onrender.com/docs) |
| ⚛️ Frontend | [churn-predictor](https://github.com/ssergionp/churn-predictor) | React (Vite), TypeScript, Recharts | [App em produção](https://churn-predictor-lilac.vercel.app) |

> ⚠️ O backend está hospedado no plano gratuito do Render — a primeira requisição pode levar de 30 a 50 segundos enquanto o serviço "acorda" após período de inatividade.

### 🔗 URL Shortener — System Design (Rate Limiting + Caching)

Encurtador de URLs em Java + Spring Boot focado em conceitos de system design: rate limiting (Redis, fixed-window), cache-aside pattern, e testes de carga documentados com k6 (~396 req/s, p95 de 22ms sob carga sustentada).

| | Repositório | Descrição |
|---|---|---|
| ☕ Backend | [url-shortener](https://github.com/ssergionp/url-shortener) | Java 21, Spring Boot 3, Redis, PostgreSQL, Testcontainers, k6, Docker, GitHub Actions |

**Destaques técnicos:**
- Rate limiting por IP via Redis (fixed-window counter), com header `Retry-After`
- Cache-aside pattern: leituras servidas pelo Redis, com fallback e repopulação automática no PostgreSQL
- Testes de carga com k6 documentados no README: comparação entre tráfego limitado (rate limiter ativo) e capacidade real do sistema (~396 req/s, 0% de falha)
- Testes de integração com Testcontainers (PostgreSQL real via Docker)

**Destaques técnicos:**
- Autenticação JWT com access token + refresh token revogável
- Login social via Google (OAuth2), com vinculação automática de contas por e-mail
- Autorização por role (USER/ADMIN), com tratamento correto de 401 vs 403
- 21+ testes automatizados (unitários e de integração)
- CI/CD via GitHub Actions
- Frontend com renovação automática e transparente de token expirado

<!--
🔜 Próximos projetos que serão adicionados aqui:
- Projeto com Spring AI
- Projeto com arquitetura de microsserviços
-->

---

### 📊 GitHub Stats

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=ssergionp&show_icons=true&theme=default)
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=ssergionp&layout=compact)
