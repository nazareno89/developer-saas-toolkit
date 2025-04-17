# 🛠️ Developer SaaS Toolkit – NestJS Backend

A backend platform designed to help development teams manage services, environments, API keys, and CI/CD statuses — all from a centralized internal portal.

Built with **NestJS**, this project demonstrates scalable architecture, clean code practices, modularity, and real-world SaaS backend features.

---

## 🔧 Features

- 🔐 JWT Authentication with role-based access (Admin & Developer)
- 🧑‍💻 Developer & Service management
- 🌐 Environment tracking (Dev, Staging, Prod)
- 🔑 API key generation & revocation (securely hashed)
- 🚦 GitHub Actions integration for CI/CD status
- 📄 API documentation per service (Markdown or links)
- 📝 Changelogs & release notes
- 🧱 Fully modular architecture (NestJS best practices)
- 🧪 Basic unit and e2e testing setup

---

## 🧬 Tech Stack

- **NestJS** + TypeScript
- **PostgreSQL** + Prisma or TypeORM
- **JWT** authentication
- **GitHub REST API** for Actions
- **Swagger** for auto-generated API docs
- **Docker** for development

---

## 🧑‍💼 Roles

| Role     | Manage Users | Manage Services | Generate API Keys | View CI Status |
|----------|---------------|-----------------|-------------------|----------------|
| Admin    | ✅            | ✅              | ✅                | ✅             |
| Developer| ❌            | ✅ (own only)   | ✅                | ✅             |