<div align="center">

# SRT · Smart Railway Technology

**Software & IoT Engineering**

_Building the digital tools that power the design, production, and maintenance of railway rolling stock._

[![Website](https://img.shields.io/badge/Website-srt--rail.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://srt-rail.com/)
[![Location](https://img.shields.io/badge/HQ-Fano%20(PU)%2C%20Italy-success?style=flat-square&logo=googlemaps&logoColor=white)](https://srt-rail.com/)

</div>

---

## About SRT

**SRT — Smart Railway Technology S.r.l.**, designs, builds, and maintains railway rolling stock and technologies for the global market. Our work spans the full breadth of the railway industry — from track works and electrification to logistics, and the design, construction, sale, rental, and after-sales service of railway machinery.

From our operational headquarters in **Fano (PU), Italy**, we operate an Industry 4.0 production hub where machinery and plants are interconnected into the company's information and logistics systems, enabling continuous production monitoring and data-driven decision making.

## Engineering at SRT

This organization is home to SRT's **software and IoT engineering** work. We design and maintain the internal applications, management platforms, and connected solutions that digitalize and optimize our industrial processes — translating the Industry 4.0 vision into the tools used every day across our operations.

## What we're building

**i4 Hub (Portale 2)** — our Industria 4.0 telemetry platform for railway maintenance vehicles. Machines in the field connect over cellular MQTT with per-machine X.509 certificates; a self-hosted Rust backend ingests, validates, and stores their telemetry, alarms, and status in a multi-tenant TimescaleDB with row-level security, so resellers and clients each see only their own fleet — including full history if a machine is sold and changes hands. Built as a clean-architecture workspace (pure domain logic → use cases → infrastructure adapters), with the database schema, security policies, and CI pipeline enforced and tested as rigorously as the application code.

**Codificatore** — our internal desktop application for material coding, tracking, and process management on the shop floor.

## Focus areas

- **Industrial IoT & connectivity** — MQTT-based telemetry ingestion, mTLS device identity, real-time monitoring across a growing fleet of maintenance machines.
- **Multi-tenant data platforms** — tenant-isolated storage (PostgreSQL/TimescaleDB with row-level security) serving both SRT's own operations and external resellers/clients.
- **Internal applications** — desktop and web platforms for material coding, tracking, and process management.
- **Data & integration** — services and pipelines that unify the company's information and logistics systems.
- **Automation** — CI/CD workflows, dependency and security scanning, and tooling that support reliable, repeatable engineering.

## Technologies

**i4 Hub — Industria 4.0 platform**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Internal applications**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## Team

| Role | Name |
|------|------|
| Scrum Master · Automation Team Leader | Giovanni Montanari |
| Full Stack Developer — i4 Hub backend & architecture | Zied Bousnina |
| Developer — i4 Hub machine-side integration · Product Owner, Portale 2 | Mattia |
| Technical Consultant — legacy systems & field experience | Alessandro |

## Contact

📍 Via del Bersaglio, 2 — 61032 Fano (PU), Italy
✉️ [giovanni.montanari@srt-rail.com](mailto:giovanni.montanari@srt-rail.com)
🔗 [srt-rail.com](https://srt-rail.com/) · [LinkedIn](https://it.linkedin.com/company/srt-rail)

---

<div align="center">
<sub>© 2026 SRT S.r.l. — Single-member company  · All rights reserved.</sub>
</div>
