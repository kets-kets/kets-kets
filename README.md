<div align="center">

# 👋 Привет

### 🚀 Full-Stack Developer | Cloud Architect | VPN Infrastructure Specialist

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Building+scalable+cloud+solutions;Designing+secure+VPN+architectures;Crafting+AI-powered+platforms;Docker+%7C+GCP+%7C+Python+%7C+React" alt="Typing SVG" />

</div>

---

## 🎯 О Мне

Разработчик с опытом в **облачных архитектурах**, **безопасности** и **автоматизации**. Работаю с production-ready системами, Clean Architecture и DevOps практиками.

### 💻 Технологии

- **Backend**: Python (Flask, AsyncIO), RESTful API, Microservices
- **Frontend**: React 19, TailwindCSS, Modern JavaScript
- **Cloud**: Google Cloud Platform (GCE, GCS, Secret Manager)
- **DevOps**: Docker, Docker Compose, CI/CD (GitHub Actions)
- **Security**: OAuth 2.0, RBAC, OWASP Top 10
- **VPN**: Xray Core, VLESS, Shadowsocks

---

## 🛠️ Технологический Стек

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-3.0-000000?style=for-the-badge&logo=flask&logoColor=white)

### Cloud & Infrastructure
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Databases & Tools
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![MyPy](https://img.shields.io/badge/MyPy-Strict-blue?style=for-the-badge)

---

## 🌟 Проекты

### 🤖 AI Tools Platform
> **Enterprise-grade AI model aggregation platform**

Унифицированная платформа для работы с генеративными AI-моделями (Replicate, OpenAI, Vertex AI). Реализована Clean Architecture с Service Layer паттерном, OAuth 2.0 аутентификацией и RBAC системой.

**Технологии**: React 19, Flask, Docker, GCP, Replicate API  
**Особенности**: Multi-provider abstraction, Rate limiting, Credits system, CI/CD

```mermaid
graph LR
    A[Client Browser] -->|HTTPS| B[Nginx Proxy]
    B --> C[React Frontend]
    B --> D[Flask Backend]
    D --> E[SQLite DB]
    D --> F[Replicate API]
    D --> G[GCS Storage]
    style D fill:#4285F4,stroke:#333,stroke-width:2px,color:#fff
```

**Архитектурные решения**:
- Service Layer для изоляции бизнес-логики
- Provider Abstraction для легкого добавления новых AI-провайдеров
- Асинхронная генерация с polling механизмом
- Structured logging (JSON) для observability

📄 [Детальный Case Study →](https://github.com/kets-kets/portfolio-case-studies/blob/main/ai-tools-platform.md)

---

### 🔐 QentVPN
> **Split Core VPN architecture for censorship circumvention**

Коммерческий VPN-сервис с архитектурой Split Core: географически распределённые узлы (Node A в России, Node B в Германии) с маскировкой трафика под HTTPS.

**Технологии**: AsyncTeleBot, Flask, Marzban, Xray Core, Docker  
**Особенности**: Dual protocol (VLESS/Shadowsocks), Telegram Mini App, Payment automation

```mermaid
graph LR
    A[Telegram Users] -->|Commands| B[Node A Russia]
    B -->|HTTPS Masked| C[Node B Germany]
    C -->|VPN Traffic| D[Internet]
    B --> E[SQLite DB]
    B --> F[Payment Gateway]
    C --> G[Xray Core]
    style B fill:#FF6B6B,stroke:#333,stroke-width:2px,color:#fff
    style C fill:#4ECDC4,stroke:#333,stroke-width:2px,color:#fff
```

**Архитектурные решения**:
- Split Core для обхода блокировок на уровне IP
- HTTPS маскировка VPN-трафика (httpx)
- Dual protocol strategy (VLESS Reality + Shadowsocks)
- Асинхронная архитектура (AsyncIO)
- OWASP Top 10 compliance

📄 [Детальный Case Study →](https://github.com/kets-kets/portfolio-case-studies/blob/main/qentvpn-architecture.md)

---

## 🎓 Подход к Разработке

Использую **Clean Architecture** и **SOLID** принципы:

- **Separation of Concerns**: Service Layer, Repository Pattern
- **Type Safety**: MyPy strict mode для Python
- **Security**: Zero-trust секреты, OWASP compliance
- **Observability**: Structured logging, health checks

---

## 🔧 Библиотеки

### 📦 [telegram-payment-handler](https://github.com/kets-kets/telegram-payment-handler)
Type-safe библиотека для обработки платежей в Telegram (ЮKassa)

### 🤖 [ai-provider-sdk](https://github.com/kets-kets/ai-provider-sdk)
Унифицированный SDK для работы с AI-провайдерами (Replicate, OpenAI, Vertex AI)

---

## 📫 Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ketsdpt)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kets-kets)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kets@example.com)

</div>

---

<div align="center">

**Разработка**: Cloud Architecture | VPN Infrastructure | AI Integration | DevOps Automation

</div>
