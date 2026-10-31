<div align="center">

<img src="assets/banner.svg" alt="Restaurant Ordering Platform" width="100%"/>

<br/>

<img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=white" alt="React Native"/> <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io"/>

<br/>

<img src="https://img.shields.io/badge/Status-Active%20development-success?style=flat-square" alt="status"/>
<img src="https://img.shields.io/badge/Source-Private%20(commercial)-lightgrey?style=flat-square" alt="source"/>

**[Request a live demo](https://rootocloud.com) · [Hire me](mailto:faizan.developer9200@gmail.com) · [More projects](https://github.com/MuhammadFaizan73)**

</div>

---

## 📌 Overview

A full restaurant ordering platform: customers order and track in a mobile app, the restaurant runs an admin panel and kitchen display, and riders handle deliveries in their own app — all behind one Next.js backend and a shared PostgreSQL database, with real-time updates.

## ✨ Key Features

### Customer App
- Browse menu and place orders
- Live order tracking

### Restaurant
- Admin panel with menu, orders and analytics
- Kitchen Display System at /kitchen

### Delivery
- Rider app with delivery flow
- Real-time status over Socket.io / Pusher

## 🏗️ Architecture

```mermaid
flowchart LR
  CA[Customer App<br/>Expo] --> API[Next.js 15<br/>Admin + API]
  RA[Rider App<br/>Expo] --> API
  K[Kitchen Display] --> API
  API --- DB[(PostgreSQL<br/>Prisma)]
  API <--> RT[Realtime<br/>Socket.io]
  RT --> CA
  RT --> RA
```

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Customer & Rider apps** | React Native (Expo) |
| **Admin + API** | Next.js 15 (App Router) · API routes |
| **Database** | PostgreSQL · Prisma |
| **Realtime** | Socket.io server (or Pusher) |
| **Auth** | JWT for mobile |
| **Dev** | Docker Compose |

<!-- SCREENSHOTS -->
<!-- /SCREENSHOTS -->

## 🔒 About the Source Code

This is a **commercial / client project**, so the source code is kept in a private repository.
This page documents what the system does and how it is built.

- 🎥 **Live walkthrough** — available on request
- 💼 **Want something similar for your business?** I build custom versions of this for clients.

## 👨‍💻 Author

**Muhammad Faizan** — Founder, [Rootocloud](https://rootocloud.com)
AI agents & automation · Web & mobile apps · Custom software

[![Website](https://img.shields.io/badge/rootocloud.com-0B1220?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rootocloud.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizan.developer9200@gmail.com)

<div align="center"><sub>© Muhammad Faizan. All rights reserved.</sub></div>
