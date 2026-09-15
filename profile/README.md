<div align="center">

# SRT · Smart Railway Technology

**Software & IoT Engineering**

[![Website](https://img.shields.io/badge/Website-srt--rail.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://srt-rail.com/)
[![Location](https://img.shields.io/badge/HQ-Fano%20(PU)%2C%20Italy-success?style=flat-square&logo=googlemaps&logoColor=white)](https://srt-rail.com/)

</div>

---

## About SRT

**SRT - Smart Railway Technology S.r.l.** designs, builds, and maintains railway rolling stock and technologies for the global market. Our work spans track works and electrification, logistics, and the design, construction, sale, rental, and after-sales service of railway machinery.

From our headquarters in Fano (PU), Italy, we run an Industry 4.0 production hub where machinery and plants are connected into the company's information and logistics systems.

## Engineering

This organization holds SRT's software and IoT work - the internal applications and connected platforms used across our operations.

### i4 Hub

Telemetry and fleet platform for railway maintenance machines. Machines connect over cellular MQTT using per-machine X.509 certificates. A self-hosted Rust backend ingests and validates their telemetry, alarms, and status into a multi-tenant TimescaleDB, where row-level security keeps each reseller and client scoped to their own fleet.

Built as a clean-architecture workspace - domain logic isolated from infrastructure, with the boundary enforced in CI. Schema changes ship as versioned, checksum-verified migrations.

**Rust · PostgreSQL / TimescaleDB · MQTT · Docker · GitHub Actions**

### Codificatore

Desktop application for material coding, tracking, and process management.

**TypeScript · React · Electron · Node.js · Prisma · SQLite**

## Team

| | |
|------|------|
| Giovanni Montanari | Scrum Master · Automation Team Leader |
| Zied Bousnina |  Developer - i4 Hub backend & architecture |
| Mattia | Developer - machine-side integration · Product Owner, Portale 2 |
| Alessandro | Technical Consultant - legacy systems & field operations |

## Contact

Via del Bersaglio, 2 - 61032 Fano (PU), Italy
[giovanni.montanari@srt-rail.com](mailto:giovanni.montanari@srt-rail.com)
[srt-rail.com](https://srt-rail.com/) · [LinkedIn](https://it.linkedin.com/company/srt-rail)

---

<div align="center">
<sub>© 2026 SRT S.r.l. - Single-member company · All rights reserved.</sub>
</div>
