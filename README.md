<div align="center">

# HARIPRASAD K

### Software Engineer · Java · AI Engineering · Full-Stack Development

Building intelligent, secure, and production-oriented software systems.

<br />

<a href="https://hariprasad-k-portfolio.vercel.app/">
<img src="https://img.shields.io/badge/PORTFOLIO-111111?style=for-the-badge&logo=vercel&logoColor=white" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/hariprasad-k-4665b0259/">
<img src="https://img.shields.io/badge/LINKEDIN-111111?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:hariprasadk716@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-111111?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br /><br />

<img src="https://komarev.com/ghpvc/?username=HARIPRASADK720&style=flat-square&color=111111&label=PROFILE+VIEWS" />

</div>

---

## ABOUT

I'm an **Information Science & Engineering graduate** focused on building reliable software across **backend engineering, full-stack development, and applied AI**.

My work combines **Java, Spring Boot, modern web technologies, RAG, Agentic AI, secure APIs, databases, and deployment** to create applications that solve practical problems.

I enjoy taking a system from:

**Problem → Architecture → Implementation → Security → Testing → Deployment**

### What I build

- ☕ Java & Spring Boot backend systems
- 🤖 AI applications using RAG and Agentic AI
- 🔎 Context-grounded LLM applications
- 💻 Modern full-stack applications
- 🔐 Secure REST APIs and authentication systems
- ⚡ Data-driven applications with PostgreSQL & Redis
- 🐳 Containerized and deployable applications

---

## ENGINEERING STACK

<table>
<tr>
<td width="50%" valign="top">

### BACKEND

`Java`  
`Spring Boot`  
`Spring Security`  
`REST APIs`  
`JPA / Hibernate`  
`JWT`  
`API Security`  
`Concurrency`

</td>

<td width="50%" valign="top">

### AI ENGINEERING

`Generative AI`  
`LLMs`  
`RAG`  
`Semantic Retrieval`  
`Agentic AI`  
`Tool Calling`  
`Prompt Engineering`  
`Grounded Generation`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### FRONTEND

`Next.js`  
`React`  
`TypeScript`  
`Tailwind CSS`  
`HTML`  
`CSS`

</td>

<td width="50%" valign="top">

### DATA & INFRASTRUCTURE

`PostgreSQL`  
`Redis`  
`Docker`  
`Docker Compose`  
`GitHub Actions`  
`Vercel`  
`Render`

</td>
</tr>
</table>

---

# FEATURED PROJECTS

## 01 · SerenityCounsellor

### AI-Powered Wellbeing & Counselling Platform

A full-stack platform combining **RAG-based AI interaction, psychometric assessment, secure authentication, counselling workflows, appointment management, and safety-oriented AI architecture**.

### Engineering Highlights

- 🔎 Grounded **Retrieval-Augmented Generation**
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
