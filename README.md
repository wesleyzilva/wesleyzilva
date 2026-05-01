# Wesley Gomes — Executive Technology Portfolio

> **High-impact digital products, data-driven solutions, and global architecture leadership**

Welcome to my executive portfolio. Here you'll find flagship projects, production-grade architectures, and insights on building technology that scales globally while maintaining security, compliance, and operational excellence.

---

## 🎯 About Me

**Senior Software Architect & Technical Leader** with 10+ years building large-scale financial and payment systems.

- 🏢 **Current:** Experian | Flexpag (Brazil's largest platform for Bills, Payments & Collections)
- 🌍 **Expertise:** Microservices, Event-Driven Architecture, Payment Systems, Real-Time Data Pipelines
- 🔐 **Specialties:** PCI DSS, LGPD, Security & Compliance, High-Availability Systems
- 📊 **Scale:** Platforms processing **100M+ transactions/month**, **400+ repositories**

---

## 🚀 Flagship Projects

### 1. **Flexpag Ecosystem** — Bills, Payments & Collections Platform
**Role:** Architect & Lead Developer | **Tech:** Java, Spring Boot, Kafka, PostgreSQL, AWS  
**Impact:** Processes 100M+ transactions monthly across 400+ microservices

- **FlexHub MS (Utilities):** Customer, Debts, Orders, Purchase microservices
- **Payment Manager:** Real-time payment orchestration (Pix, Boleto, Credit Card)
- **SmartPOS Backend:** IoT payment devices integration
- **Totem API:** Points-of-sale unification

📚 [Flexpag Ecosystem Documentation](../ECOSYSTEM-flexpag.md)

### 2. **Partners Portal (BFF + Frontend)**
**Role:** Full-stack Lead | **Tech:** Angular 17, Tailwind, Java Spring Boot  
**Status:** Production | **Users:** 1000+ partner organizations

- Responsive dashboard for partner management
- Real-time KPI monitoring and financial analytics
- Smart POS device integration
- RBAC (Role-Based Access Control)

📚 [BFF Architecture](../aquitetura_flexpag/README-ARQUITETURA.md)

### 3. **Payment Gateway Integration Layer**
**Role:** Principal Architect | **Tech:** Java, WebClient (Reactive), Spring Cloud  
**Handles:** Multi-channel payment processing (PIX, Boleto, Cards)

- PCI DSS Level 1 compliance
- Sub-millisecond latency orchestration
- Event-driven settlement reconciliation

---

## 🏗️ Architecture Highlights

### Microservices & Event-Driven Design
```
FlexHub (Utilities) ──→ Payment Manager ──→ PIX/Boleto/Card Gateways
         ↓
      Kafka Topics (Events)
         ↓
  Analytics Backend ← Real-time data pipeline
```

### Key Principles
✅ **Decoupled services** via Kafka event streaming  
✅ **Database per service** pattern (no shared monolithic DB)  
✅ **SOLID principles** in service design  
✅ **Comprehensive monitoring** via Datadog, Grafana  
✅ **Infrastructure as Code** (Terraform, Docker, Kubernetes)

📊 [Full Architecture Diagram](../arquitetura_flexpag/ARQUITETURA-GERAL.md)

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Backend** | Java 17/21, Spring Boot 3.x, Spring Cloud, WebFlux |
| **Event Streaming** | Apache Kafka, RabbitMQ |
| **Database** | PostgreSQL, H2 (testing), Redis |
| **Frontend** | Angular 17+, TypeScript, Tailwind CSS, Signals |
| **Infrastructure** | AWS (ECS, Lambda, RDS), Docker, Kubernetes |
| **Observability** | Datadog, Grafana, ELK Stack |
| **Testing** | JUnit 5, Mockito, Jest, Karma |
| **Security** | OAuth 2.0, JWT, PCI DSS, LGPD compliance |

---

## 📚 Documentation & Guides

- 📖 [Getting Started with Flexpag](../GETTING-STARTED.md)
- 🏛️ [Architecture Overview](../arquitetura_flexpag/ARQUITETURA-GERAL.md)
- 🗄️ [Database Schema & Mapping](../RDS%20banco%20schema%20tabela%20Flexpag.txt)
- 🔒 [Security & Compliance](../SECURITY-flexpag.md)
- ✅ [Testing Strategy](../TESTING-flexpag.md)
- 🚀 [Local Setup Instructions](../INSTRUCOES-ACESSO-LOCAL-FLEXPAG.md)

---

## 🔗 Quick Links

| Resource | Link |
|----------|------|
| **GitHub Profile** | https://github.com/wesleyzilva |
| **Email** | wesley.silva@br.experian.com |
| **LinkedIn** | (Add when needed) |
| **Flexpag Docs** | [Private repo — contact for access] |

---

## 📊 Key Metrics

- **Services:** 40+ microservices across Flexpag ecosystem
- **Languages:** Java, TypeScript, Python, Kotlin
- **CI/CD:** GitLab CI/CD + GitHub Actions
- **Uptime:** 99.95% SLA (production grade)
- **Teams Led:** 5-8 engineers across multiple squads

---

## 🎓 Open Source & Community

Contributing to the Flexpag ecosystem and maintaining best practices for:
- ✅ Clean architecture
- ✅ Security hardening
- ✅ Performance optimization
- ✅ LGPD/PCI compliance

---

## 🤝 Let's Connect

If you're interested in:
- 🏗️ **Architecture consulting** for payment/fintech systems
- 💼 **Technical leadership** roles
- 🔐 **Compliance & security** architecture
- 📊 **Scalable system design**

**Reach out:** wesley.silva@br.experian.com

---

**Last Updated:** May 1, 2026 | **Profile Version:** 1.0
