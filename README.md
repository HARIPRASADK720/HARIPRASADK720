You're right. The problem is that the **external GitHub Stats images are failing**, so even a correct README can show broken images.

For a **truly reliable 10/10 README**, I recommend removing **ALL dynamic stats/images that depend on third-party APIs**. Keep only GitHub-native Markdown/HTML and your project links.

Use this version — **no GitHub Stats, no streak cards, no external stats API**:

````markdown
<div align="center">

# HARIPRASAD K

### Software Engineer · Java · AI Engineering · Full-Stack Development

Building intelligent, secure, and production-oriented software systems.

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://hariprasad-k-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hariprasad-k-4665b0259/)
[![Email](https://img.shields.io/badge/Email-111111?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hariprasadk716@gmail.com)

</div>

---

## ABOUT

I'm an **Information Science & Engineering graduate** focused on building reliable software across **backend engineering, full-stack development, and applied AI**.

My work combines **Java, Spring Boot, modern web technologies, RAG, Agentic AI, secure APIs, databases, and deployment** to create practical software systems.

I enjoy taking a problem from:

**Problem → Architecture → Implementation → Security → Testing → Deployment**

### What I Build

- ☕ Java & Spring Boot backend systems
- 🤖 AI applications using RAG and Agentic AI
- 🔎 Context-grounded LLM applications
- 💻 Modern full-stack applications
- 🔐 Secure REST APIs and authentication systems
- ⚡ Data-driven applications with PostgreSQL & Redis
- 🐳 Containerized and deployable applications

---

## ENGINEERING STACK

### Backend

`Java` · `Spring Boot` · `Spring Security` · `REST APIs` · `JPA / Hibernate` · `JWT`

### AI Engineering

`Generative AI` · `LLMs` · `RAG` · `Semantic Retrieval` · `Agentic AI` · `Prompt Engineering`

### Frontend

`Next.js` · `React` · `TypeScript` · `Tailwind CSS` · `HTML` · `CSS`

### Data

`PostgreSQL` · `Redis`

### Infrastructure & Tools

`Docker` · `Docker Compose` · `Git` · `GitHub` · `GitHub Actions` · `Vercel` · `Render`

---

# FEATURED PROJECTS

## 01 · SerenityCounsellor

### AI-Powered Wellbeing & Counselling Platform

A full-stack platform combining **RAG-based AI interaction, psychometric assessment, secure authentication, counselling workflows, appointment management, and safety-oriented application architecture**.

### Engineering Highlights

- 🔎 Retrieval-Augmented Generation for context-grounded responses
- 🧠 Context-aware AI conversation architecture
- 🔐 JWT authentication and role-based authorization
- 🛡️ BOLA / IDOR protection
- ⚡ Concurrency protection for appointment booking
- 🔄 Refresh-token rotation and replay detection
- 🚦 API rate limiting
- 📡 Asynchronous event-driven processing
- 🧪 Unit and integration testing
- 🐳 Dockerized development environment
- ⚙️ GitHub Actions CI workflow

### Architecture

```text
                    ┌─────────────────────┐
                    │   Next.js Frontend  │
                    │     TypeScript      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Spring Boot API   │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
       ┌────────────┐   ┌────────────┐   ┌────────────┐
       │  Security  │   │    RAG     │   │  Services  │
       └────────────┘   └────────────┘   └────────────┘
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ PostgreSQL + Redis  │
                    └─────────────────────┘
````

**Stack**

`Java` · `Spring Boot` · `Spring Security` · `Spring AI`
`Next.js` · `TypeScript` · `PostgreSQL` · `Redis`
`Docker` · `GitHub Actions` · `JUnit`

**Repository**

[View SerenityCounsellor →](https://github.com/HARIPRASADK720/SerenityCouncellor)

---

## 02 · QuizCogniVault

### Knowledge-Adaptive Assessment Intelligence

An AI-powered assessment platform combining **RAG, controlled Agentic AI workflows, adaptive assessment, AI tutoring, knowledge profiling, and technical interview simulation**.

### Intelligence Loop

```text
        ASSESS
          ↓
      UNDERSTAND
          ↓
        ADAPT
          ↓
       EXPLAIN
          ↓
      RECOMMEND
          ↓
       REASSESS
```

### Engineering Highlights

* 🤖 Controlled Agentic AI workflow
* 🔎 Grounded RAG with source attribution
* 📐 Adaptive assessment and difficulty logic
* 🧑‍🏫 AI Tutor with multiple explanation modes
* 💼 AI-powered technical interview simulation
* 📊 Knowledge profiling and learning journey
* 🔐 JWT authentication and role-based access
* ⚡ Redis caching
* 🗄️ PostgreSQL persistence
* 🧪 Backend testing
* 🚀 Deployed application

**Stack**

`Java` · `Spring Boot` · `Spring AI` · `Next.js`
`TypeScript` · `PostgreSQL` · `Redis` · `JWT` · `RAG`

**Repository**

[View QuizCogniVault →](https://github.com/HARIPRASADK720/QuizCogniVault)

**Live Application**

[Launch QuizCogniVault →](https://frontend-seven-lime-80.vercel.app/)

---

## 03 · GreenLeaf Nursery

### Full-Stack Digital Nursery Platform

A modern full-stack application focused on delivering a polished digital experience for nursery management and online plant shopping.

**Focus**

`Full-Stack Development` · `REST APIs` · `Database Integration` · `Modern UI` · `Deployment`

[View GreenLeaf Nursery →](https://github.com/HARIPRASADK720/Nurserywebsite)

---

## 04 · Developer Portfolio

### Personal Engineering Portfolio

A modern portfolio showcasing my projects, technical capabilities, and professional profile.

**Focus**

`Frontend Development` · `Responsive UI` · `Portfolio Engineering` · `Web Deployment`

[View Portfolio →](https://hariprasad-k-portfolio.vercel.app/)

---

# AI ENGINEERING

My AI work focuses on integrating intelligence into **real application architectures**, rather than treating an LLM as an isolated feature.

### Retrieval-Augmented Generation

```text
User Query
     ↓
Retrieval
     ↓
Relevant Context
     ↓
Prompt Construction
     ↓
LLM Generation
     ↓
Grounded Response
```

### Agentic AI

```text
Understand
    ↓
Decide
    ↓
Select Action / Tool
    ↓
Execute
    ↓
Evaluate
    ↓
Respond
```

The goal is to build AI systems that are **grounded, controlled, context-aware, and connected to real application workflows**.

---

# ENGINEERING MINDSET

> **Architecture over buzzwords.**

Good software is not defined by the number of technologies in the stack.

It is defined by how well the system handles:

**Correctness · Security · Reliability · Maintainability · Scalability**

### Development Approach

```text
Problem
   ↓
Understand the Domain
   ↓
Design the Architecture
   ↓
Build the Core System
   ↓
Integrate Intelligence Where It Adds Value
   ↓
Secure Critical Paths
   ↓
Test Important Behaviour
   ↓
Containerize
   ↓
Deploy
```

---

# CURRENT FOCUS

| Area             | Focus                                        |
| ---------------- | -------------------------------------------- |
| ☕ Backend        | Java · Spring Boot · REST APIs               |
| 🏗️ Architecture | System Design · Backend Architecture         |
| 🤖 AI            | RAG · Agentic AI · LLM Applications          |
| 🔐 Security      | Authentication · Authorization · Secure APIs |
| 🗄️ Data         | PostgreSQL · Redis                           |
| 🚀 DevOps        | Docker · CI/CD · Deployment                  |

---

# CONNECT

<div align="center">

### Software Engineering · AI Systems · Full-Stack Development

<br/>

[![Portfolio](https://img.shields.io/badge/VISIT_PORTFOLIO-111111?style=for-the-badge\&logo=vercel\&logoColor=white)](https://hariprasad-k-portfolio.vercel.app/)

[![LinkedIn](https://img.shields.io/badge/CONNECT_ON_LINKEDIN-111111?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/hariprasad-k-4665b0259/)

[![Email](https://img.shields.io/badge/GET_IN_TOUCH-111111?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:hariprasadk716@gmail.com)

<br/>

**HARIPRASAD K**

`Java` · `Spring Boot` · `Full-Stack` · `RAG` · `Agentic AI`

<br/>

<sub>Build with purpose. Learn continuously. Ship consistently.</sub>

</div>
```

**This version removes the source of the broken cards entirely.** Your profile will still look polished even if an external service goes down, because the core README doesn't depend on dynamic GitHub-stat image servers.
