<div align="center">

# Rushi Bankar

**AI / ML Engineer &nbsp;·&nbsp; Backend Developer**

I build end-to-end intelligent systems — from data ingestion and LLM pipelines<br/>
to the production APIs and interfaces people actually use.

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-rushi-iota.vercel.app)
[![Email](https://img.shields.io/badge/Email-rushibankar2103@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rushibankar2103@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-rushibankar3-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rushibankar3)

</div>

---

## About

- 🎓 Final-year **B.E. Computer Science** student at **Wadia College of Engineering, Pune** (2023–2027), CGPA **8.0/10**
- 🧠 I work across the full pipeline: **scraping & data engineering → LLM/ML pipelines → typed APIs → React/Streamlit interfaces → Docker & AWS**
- 💼 Recently interned on the backend team at **Nuzzy**, shipping AI-powered review intelligence for a pet-care marketplace
- ⚙️ Currently going deeper into **system design**, **LLM orchestration**, and **DSA** (61 C++ problems and counting)
- 🚀 Open to **AI/ML and backend engineering** roles for 2027

---

## Experience

### Software Engineering Intern — Nuzzy
`Sep 2026 – Oct 2026` &nbsp;·&nbsp; **TypeScript · Next.js 16 · AWS Amplify Gen 2 · DynamoDB · Claude / OpenRouter**

Nuzzy is a pet-care platform connecting pet parents with vets, boarding, daycare, grooming and pet-friendly cafés. On the `Nuzzy-HQ/api` team I owned the **Places discovery and review-intelligence pipeline**, shipping **23 pull requests (21 merged)** across **64 commits**.

- Designed a **multi-model review-analysis pipeline with Claude as the arbiter model**, and led the migration of the agent pipeline from **Vertex AI to OpenRouter** behind a feature flag.
- Added review ingestion and pet-policy extraction for **five sources — Google, Zomato, TripAdvisor, Agoda and Booking.com** — with deduplication, versioning and graceful scrape recovery.
- Made pipeline runs **incremental** (review versioning + AI-stage reuse) and replaced full-table scans with **indexed DynamoDB queue reads**, cutting refresh cost and latency.
- Built admin tooling for **run cancellation**, **escalation review** and place management, and kept published listings live through reruns via **atomic pipeline completion**.
- Delivered place-detail enrichment (management statements, amenities, pricing tiers, pet policies), Google-lookup place creation and collision-safe slug generation.

---

## Featured Projects

### 🌾 MandiGhar — community group-buying for Indian farmers
`NestJS 11` · `Prisma` · `PostgreSQL 16` · `Redis + BullMQ` · `Next.js 15` · `Razorpay` · `Docker`

A production-shaped monorepo that connects farmers directly with locality-based residential communities. Customers start or join a group order; KYC-verified farmers bid on the aggregated demand; the first farmer with enough stock accepts, delivers to pickup points, and gets settled two business days later — with automatic refunds if no farmer accepts.

- Three apps in one workspace: **NestJS REST API**, **customer/farmer PWA** and an **operations console**, plus a shared TypeScript package.
- Handles **tiered group pricing, Razorpay payments & webhooks, encrypted KYC (AES-256 / SHA-256), procurement with demand buffers, settlement ledgers, and multi-channel notifications** (FCM, MSG91, SendGrid).
- **PostgreSQL + PostGIS geographies**, BullMQ background workers, structured JSON logging, Swagger docs, CI/CD to EC2 via GitHub Actions.

### 🏥 ClinixOS — multi-tenant clinic operations SaaS
`FastAPI` · `SQLAlchemy` · `React 18` · `Vite` · `PostgreSQL` · `Cashfree` · `Docker`

An enterprise-style B2B SaaS for clinics and hospitals in India — online patient booking, walk-in reception, token queues, prescriptions with PDF generation, automated follow-ups, analytics and subscription billing. Built over **272 commits** with strict tenant isolation.

- **RBAC + tenant middleware** across every route, subscription guards, audit logging and signed payment webhooks.
- **Patient portal, doctor scheduling, public TV queue display**, broadcast notifications and **i18n in English, Hindi and Marathi**.
- ReportLab/OpenPyXL reporting, Capacitor mobile shell, Docker Compose + Nginx deployment.

### 📍 Location Review Analyzer — evidence-backed place intelligence
`Python` · `Streamlit` · `Groq (Llama 3.3/3.1)` · `Apify` · `Plotly`

Scrapes up to 100 real Google Maps reviews for any place and produces a grounded verdict through a **two-model LLM pipeline with deterministic Python scoring**.

- Model A extracts aspects, themes and temporal trends; a guardrail model flags fake reviews; Model B independently verifies the first pass against the source reviews.
- The final score is computed by **weighted Python logic — models surface evidence, they never decide the verdict** — with hallucination and contradiction detection on top.

### 📰 AI News Automator — autonomous India-first news agent
`Python` · `Ollama` · `Stable Diffusion` · `RSS / Reddit / Google Trends` · `SQLite`

A fully automated agent that ingests multi-source news, prioritizes Indian, breaking and finance-critical stories, generates social copy and news-style images **locally (Ollama + Stable Diffusion)**, and posts to X and Instagram — with SQLite deduplication and event-driven monitoring.

---

## More Projects

| Project | What it does | Stack |
|---|---|---|
| **[Smart Inventory AI](https://github.com/rushibankar3/Smart-Inventory-project)** | XGBoost demand forecasting + EOQ optimisation with reorder points, safety stock and understock/overstock decisions | `XGBoost` `FastAPI` `Streamlit` |
| **[Stock Market Sentiment Analysis](https://github.com/rushibankar3/Stock-market-sentiment-Analysis)** | VADER tweet sentiment joined with Yahoo Finance OHLCV data to model price movement, served through Streamlit | `NLTK` `TensorFlow/Keras` `scikit-learn` |
| **[Credit Card Fraud Detection](https://github.com/rushibankar3/Credit-card-fraud-detection-)** | Imbalanced-class pipeline (0.17% fraud) comparing LR, Random Forest, XGBoost and LightGBM with SMOTE and threshold tuning | `XGBoost` `LightGBM` `imbalanced-learn` |
| **[Cricket Data Analysis](https://github.com/rushibankar3/data_analysis)** | Kohli ODI performance analysis with Matplotlib/Seaborn — distributions, strike-rate relationships and match trends | `Pandas` `Matplotlib` `Seaborn` |
| **DSA in C++** | 61 LeetCode/NeetCode problems organised by topic, 231 commits of consistent practice | `C++` |

*Walkthroughs and demos for private projects are available on request.*

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI & Machine Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![LLM Pipelines](https://img.shields.io/badge/LLM%20Pipelines-Claude%20%7C%20OpenRouter%20%7C%20Groq%20%7C%20Ollama-412991?style=flat-square&logo=anthropic&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## Education

**B.E. Computer Science** — Wadia College of Engineering, Pune &nbsp;·&nbsp; *2023 – 2027* &nbsp;·&nbsp; **CGPA 8.0/10**

---

<div align="center">

### Let's build something useful

[![Portfolio](https://img.shields.io/badge/portfolio-rushi-iota.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-rushi-iota.vercel.app)
[![Email](https://img.shields.io/badge/email-rushibankar2103@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rushibankar2103@gmail.com)
[![GitHub](https://img.shields.io/badge/github-rushibankar3-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rushibankar3)

</div>
