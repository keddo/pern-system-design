# 🏗️ Large-Scale System Design & Development with the PERN Stack

> My learning journey: building production-grade, scalable systems with **PostgreSQL, Express, React, and Node.js**.

![Status](https://img.shields.io/badge/status-learning%20in%20progress-blue)
![Stack](https://img.shields.io/badge/stack-PERN-success)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📖 About This Repo

This repository documents my step-by-step path from **writing CRUD apps** to **designing and building large systems**: systems that handle many users, stay reliable under load, and remain easy to change as they grow.

Each lesson has its own folder with notes, code, and exercises. I commit as I learn, so the history shows real progress.

## 🎯 Goals

- Understand **how large systems are designed**, not just how to code features
- Build a **real full-stack project** that grows from a simple app into a scalable system
- Learn the trade-offs behind caching, queues, scaling, and database design
- Practice **clean architecture**, testing, security, and deployment

## 🧰 Tech Stack

| Layer | Technology | Role |
|---|---|---|
| **P**ostgreSQL | Relational database | Stores data reliably with transactions and strong consistency |
| **E**xpress | Node.js web framework | Builds the REST API |
| **R**eact | UI library | Builds the frontend |
| **N**ode.js | JavaScript runtime | Runs the server |
| Extras (later) | Redis, Docker, Nginx, BullMQ, GitHub Actions | Caching, containers, load balancing, background jobs, CI/CD |

## 🗺️ Learning Roadmap

### Phase 1: Foundations
- [ ] 01: What "large system" means + PERN overview + environment setup
- [ ] 02: Node.js & Express fundamentals (routing, middleware, errors)
- [ ] 03: PostgreSQL fundamentals (SQL, relations, constraints)
- [ ] 04: React fundamentals (components, state, data fetching)

### Phase 2: Building a Real App
- [ ] 05: Project architecture & folder structure (layered design)
- [ ] 06: REST API design (resources, status codes, versioning, pagination)
- [ ] 07: Database design & migrations (normalization, indexes)
- [ ] 08: Authentication & authorization (JWT, refresh tokens, roles)
- [ ] 09: Validation, error handling & logging
- [ ] 10: Testing (unit, integration, end-to-end)

### Phase 3: Scaling Up
- [ ] 11: Performance: query optimization, indexing, connection pooling
- [ ] 12: Caching with Redis
- [ ] 13: Background jobs & message queues
- [ ] 14: Horizontal scaling, load balancing & stateless services
- [ ] 15: Database scaling: replication, read replicas, partitioning
- [ ] 16: Rate limiting, security hardening (OWASP Top 10)

### Phase 4: Production
- [ ] 17: Docker & Docker Compose
- [ ] 18: CI/CD with GitHub Actions
- [ ] 19: Monitoring, metrics & observability
- [ ] 20: Monolith vs microservices: when and how to split

### 🚀 Capstone Project
A full-featured, scalable application built across all lessons and deployed to production.

## 📁 Repository Structure

```
pern-system-design/
├── lessons/
│   ├── 01-foundations/
│   │   ├── notes.md
│   │   └── exercises/
│   └── ...
├── project/
│   ├── server/        # Node.js + Express API
│   ├── client/        # React frontend
│   └── database/      # Migrations & seeds
└── README.md
```

## ⚙️ Getting Started

```bash
# Clone the repo
git clone https://github.com/<your-username>/pern-system-design.git
cd pern-system-design

# Backend
cd project/server
npm install
npm run dev

# Frontend (new terminal)
cd project/client
npm install
npm run dev
```

**Requirements:** Node.js (LTS), PostgreSQL, Git

## 📚 Resources

- [Node.js Docs](https://nodejs.org/docs)
- [Express Docs](https://expressjs.com)
- [PostgreSQL Docs](https://www.postgresql.org/docs/)
- [React Docs](https://react.dev)
- *Designing Data-Intensive Applications* by Martin Kleppmann
- [System Design Primer](https://github.com/donnemartin/system-design-primer)

## 📝 Progress Log

| Date | Lesson | What I Learned |
|---|---|---|
| 2026-10-14 | 01 | Started the journey: PERN overview & setup |

---

⭐ If you're learning too, feel free to follow along, fork, or open an issue with suggestions!
