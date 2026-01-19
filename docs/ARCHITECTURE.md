# Arquitetura do Sistema
Documentação técnica principal.


🏗️ System Architecture

Frontend (Web / Mobile / Desktop)
   ├─ Corporate UI
   ├─ Virtual Assistant
   ├─ Internal Chat
   ├─ Service Supervision
   └─ Academy + Library

Backend (Main API)
   ├─ Authentication & RBAC
   ├─ Ticket Engine
   ├─ AI Orchestrator
   ├─ Inventory Management
   └─ Reporting

AI Engine (Open Source)
   ├─ Main Model (Mistral / LLaMA)
   ├─ Cognitive Memory
   └─ Priority Engine

Databases
   ├─ Master Database (PostgreSQL)
   └─ Mirrored Database (Cloudflare)


---

🗄️ Data Architecture

🥇 Master Database

PostgreSQL (Render)


Responsibilities:

Users and permissions

Tickets and departments

Internal chat

Courses, library, certificates



---

🪞 Mirrored Database (Operational Continuity)

Cloudflare D1 / R2


Functions:

Encrypted replication

Continuous backup

Automatic failover



---

☁️ Hosting & Infrastructure

Hosting: Render.com

Databases: Render PostgreSQL + Cloudflare backup


Linux / WSL unified build pipeline.


---

📱🖥️ Multiplatform & IoT

Web (SPA / PWA)

Android (Capacitor)

iOS (Capacitor)

Desktop (Tauri)

Future IoT dashboards and terminals



---

👥 Governance & Access Control

Scalable RBAC system:

👑 General Administrator (1)

🧠 Department Supervisors (12+)

✍️ Content Managers (6+)

👤 Corporate Users (unlimited)



---

🧩 AI Strategy

Initial phase:

Single open‑source model (Mistral or LLaMA)


Future evolution:

Multiple specialized models

Institutional training

Proprietary corporate AI



---

🔐 Security & Quality Standards

Based on international standards:

CIA Triad: Confidentiality, Integrity, Availability

ISO 27001 — Information Security

ISO 9001 — Quality Management

ITIL — Service Management

OWASP Top 10 — Web Security



---

⚙️ Technology Stack (100% Open Source)

Frontend: React / Vue + TypeScript

Backend: FastAPI or NestJS

Database: PostgreSQL

Cache / Queues: Redis

AI: Mistral / LLaMA + LangChain / Haystack


