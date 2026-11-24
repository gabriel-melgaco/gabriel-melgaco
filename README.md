# Hi, I'm Gabriel Melgaço 👋

**Full-Stack Developer** — Python & Django · Multi-Vendor Marketplaces · Offline-First Applications · Linux Infrastructure

I build systems that have to work in the real world: sales floors without internet, inventory that must
reconcile with an ERP, and servers that cannot afford to be down. I'm a Brazilian Army officer with 11
years in technology and management, and I've been building with Python and Django for about three years —
from the data model to the server it runs on.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gabriel--melgaco-informational?style=flat&logo=linkedin&logoColor=white&color=2bbc8a)](https://www.linkedin.com/in/SEU-SLUG-AQUI/)
[![Email](https://img.shields.io/badge/Email-megdev99%40gmail.com-informational?style=flat&logo=gmail&logoColor=white&color=2bbc8a)](mailto:megdev99@gmail.com)
[![Python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=2bbc8a)](https://www.python.org/)

## 🔭 What I'm working on

- 🛫 **Aviation logistics** — inventory and maintenance-order control for an Army Aviation Battalion:
  aircraft parts, RMS/FSM/REQ orders, material movement and traceability.
- 🛒 **Multi-vendor marketplace** — Django + React with per-seller order splitting, Stripe Connect payouts
  and Melhor Envio shipping using each seller's own OAuth2 credentials.
- 🧾 **Offline-first POS** — an Electron + SQLite + Django point-of-sale built to keep selling with no
  network, then synchronize idempotently: conflict handling, safe recovery of a lost installation and
  version compatibility gates between terminal and server.

## 🚀 Featured projects

### 🛫 SGE — Aviation Inventory Management System

[![Repo](https://img.shields.io/badge/GitHub-aviation__management__system-181717?style=flat&logo=github&logoColor=white)](https://github.com/gabriel-melgaco/aviation_management_system)

Inventory and order management built for an **Army Aviation Battalion**, replacing spreadsheet control
of aircraft parts.


`Django 5.2` · `PostgreSQL 15` · `Docker` · `Gunicorn + Nginx` · `openpyxl` · `Bootstrap` · `Chart.js`

---

### 🛒 Marketplace Academia

[![Repo](https://img.shields.io/badge/GitHub-marketplace-181717?style=flat&logo=github&logoColor=white)](https://github.com/gabriel-melgaco/marketplace)

Multi-vendor marketplace for buying and selling gym equipment in Brazil. One cart, one checkout, many
sellers — and the money has to land in the right account.

- **Order splitting per seller** at checkout, with each resulting order routed independently through
  payment and shipping.
- **Stripe Connect** Payment Intents — platform commission plus seller payouts.
- **Melhor Envio** shipping orchestration with **per-seller OAuth2** credentials, so each seller's own
  freight contract is used.
- JWT stored in **HttpOnly cookies**, Google OAuth2 login, MinIO image storage, Resend transactional
  email, ViaCEP postal lookup and auto-generated OpenAPI documentation.
- Structured logging, background processing with Celery and an explicit order-status state machine.

`Django 5.1` · `DRF` · `Daphne + Channels` · `PostgreSQL` · `Redis` · `Celery` · `React + Vite` ·
`Tailwind` · `Stripe` · `Docker`

---

### 🧾 Offline-first POS terminal *— private, client-owned*

Electron · SQLite · TypeScript · Django

A point-of-sale that operates fully offline and synchronizes later. The hard part isn't the UI — it's what
happens when the network dies mid-shift: local event outbox with sequence numbers, idempotent batch upload,
deferred/duplicate/rejected handling, safe recovery that swaps a damaged database without losing pending
sales, and compatibility policies that block sync on an outdated client while keeping the store selling.

### 🏪 Storefront with ERP and payment gateway *— private, client-owned*

Python · Django · PostgreSQL · JavaScript

Product catalog with grouped public cards over separate internal SKUs, stock reservation and lot allocation
at checkout, Bling ERP synchronization (customers, orders, stock movements) and Mercado Pago integration
with server-side fee recomputation and webhook-authenticated confirmation.

> These two are client projects under NDA. Happy to walk through the architecture and the tricky parts in
> an interview.

## 🛠️ Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Electron](https://img.shields.io/badge/Electron-191970?style=flat&logo=electron&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat&logo=zabbix&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat&logo=wireguard&logoColor=white)

**Also:** REST API design, webhooks and idempotency, OAuth2 integrations, automated testing (pytest,
Vitest), CI with GitHub Actions, and an unhealthy respect for backups that have never been restored.

## 📫 Beyond code

- ✈️ Brazilian Army officer — maintenance and logistics in an aviation unit, where I learned that a system
  either solves an operational problem or it's decoration.
- 🎓 Computer Engineering undergraduate; background in Military Sciences and Information Technology.
- 🌎 Open to **remote roles** or relocation. Portuguese native, English B1 (comfortable with technical docs).
- 📫 Reach me at [megdev99@gmail.com](mailto:megdev99@gmail.com) or on
  [LinkedIn](https://www.linkedin.com/in/gabriel-melga%C3%A7o-614a18290/).

---

<sub>Currently going deep on: offline-first synchronization, safe automated updates for desktop apps, and
Django performance.</sub>
# gabriel-melgaco
