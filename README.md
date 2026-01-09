# 👋 Hi, I'm Hassan Ribery  

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=550&lines=Senior+Full-Stack+Developer;TypeScript+%7C+Node.js+%7C+React;Clean+Architecture+%26+Scalable+Systems" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Code-TypeScript-blue?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/SSR-Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge&color=blue" />
</p>

---

## 🧠 About Me

🚀 **Senior Full-Stack Developer** specializing in **scalable**, **type-safe**, and **clean architecture** systems.

- Clean Architecture & Dependency Injection  
- Enterprise-grade APIs  
- TypeScript everywhere  
- Performance & maintainability first  

---

## 🛠️ Tech Stack

### 💻 Languages
<p>
  <img src="https://skillicons.dev/icons?i=ts,js" />
</p>

### ⚙️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,mongodb" />
</p>

- **InversifyJS** for Dependency Injection

### 🌐 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs" />
</p>

---

## 🏗️ System Architecture (Clean Architecture)

```mermaid
flowchart TB

    UI[Next.js / React UI]
    API[NestJS API Layer]
    CTRL[Controllers]
    UC[Use Cases / Services]
    DI[Inversify Container]
    DOMAIN[Domain Entities]
    REPO[Repositories]
    DB[(MongoDB)]

    UI -->|HTTP / REST| API
    API --> CTRL
    CTRL --> UC
    UC --> DOMAIN
    UC --> DI
    DI --> REPO
    REPO --> DB
