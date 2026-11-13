<div align="center">

  <img src="https://raw.githubusercontent.com/Livinns/.github/main/profile/assets/banner.png" alt="Livinns Brand Banner" width="480" />

  # 🏠 Livinns

  ### **India's First Property Management Platform**
  *Autonomous Student Housing, Co-Living & Multi-Hostel Operations Ecosystem*

  <p align="center">
    <a href="https://livinns.com"><img src="https://img.shields.io/badge/Marketplace-livinns.com-E11D48?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Marketplace" /></a>
    <a href="https://livinns.app"><img src="https://img.shields.io/badge/Operations_OS-livinns.app-0284C7?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Operations OS" /></a>
    <a href="https://github.com/Livinns/livinns-architecture"><img src="https://img.shields.io/badge/Architecture-Arch__Nov__26-10B981?style=for-the-badge&logo=git&logoColor=white" alt="Architecture" /></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/React-19.2-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19" />
    <img src="https://img.shields.io/badge/Expo-SDK_57-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo 57" />
    <img src="https://img.shields.io/badge/TanStack-Start_%26_Router-FF4154?style=flat-square&logo=react-table&logoColor=white" alt="TanStack" />
    <img src="https://img.shields.io/badge/TailwindCSS-v4.2-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind v4" />
    <img src="https://img.shields.io/badge/Supabase-PostgreSQL_17-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase PG17" />
    <img src="https://img.shields.io/badge/MongoDB_Atlas-GeoJSON_2dsphere-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB Atlas" />
    <img src="https://img.shields.io/badge/Cloudflare-$0.00_Zero_Egress-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  </p>

</div>

---

## 🚀 The 6-Repository Ecosystem

The Livinns platform decouples into 6 specialized repositories:

| Repository | Scope | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| [**`livinns.com`**](https://github.com/Livinns/livinns.com) | **Public Discovery Marketplace**<br>6,761+ verified PGs across 12 cities, sub-10ms GeoJSON radial search, college clusters, and 360° virtual tours. | React 19, TanStack Start, Nitro, Leaflet, MongoDB 2dsphere | `Production / Active` |
| [**`livinns.app`**](https://github.com/Livinns/livinns.app) | **Autonomous Property Operations SaaS**<br>Multi-hostel operating system, dynamic bed state machine grid, automated dues engine, UPI screenshot reconciler, and statutory police link. | React 19, TanStack Start, Nitro, TailwindCSS v4, Supabase PG17 | `Production / Active` |
| [**`livinns-find-my-pg`**](https://github.com/Livinns/livinns-find-my-pg) | **Student & Parent Discovery App (Native)**<br>Hyper-fast mobile app for discovering verified hostels, inspecting 360° tours, and instant bed locking with advance token payments. | React Native 0.86, Expo 57, React 19, Cashfree Native | `In Development` |
| [**`livinns-tenants-app`**](https://github.com/Livinns/livinns-tenants-app) | **Resident Living Companion App (Native)**<br>Digital stay passbook, 1-tap UPI QR rent payment, KYC document vault, weekly mess attendance toggles, and maintenance ticket desk. | React Native 0.86, Expo 57, React 19, Supabase Realtime | `In Development` |
| [**`livinns-pg-management-app`**](https://github.com/Livinns/livinns-pg-management-app) | **Hostel Owner & Staff Field OS (Native)**<br>Autonomous property operations on the move: instant desk cash collection, voice-to-expense logging (`/kharcha`), live bed matrix, and move-out inspection. | React Native 0.86, Expo 57, React 19, Baileys ChatOps | `In Development` |
| [**`livinns-architecture`**](https://github.com/Livinns/livinns-architecture) | **Single Source of Truth & Master Context Hub**<br>Central technical blueprints: `Arch_Nov_26` schemas, live-audited `Existing_Structure`, workflows 01-07, and Uncle Anton bare-metal runbooks. | Markdown, SQL, JSON Specs, Multi-Cloud Audits | `Canonical Truth` |

---

## ⚡ Distributed Architecture Topology

```
                                  Livinns Core Topology
                                            │
    ┌───────────────────────────────────────┼───────────────────────────────────────┐
    │                                       │                                       │
┌───▼───────────────────────────┐   ┌───────▼───────────────────────────┐   ┌───────▼───────────────────────────┐
│     CLOUD DATA PLANE (MUMBAI) │   │     CLOUDFLARE 3-ACCOUNT FLEET    │   │      BARE-METAL GROUND NODE       │
├───────────────────────────────┤   ├───────────────────────────────────┤   ├───────────────────────────────────┤
│ • Supabase PostgreSQL 17      │   │ • Account 1 (App): D1 activities, │   │ • Uncle Anton (HP Compaq 6005)    │
│   (17 Relational Tables + RLS)│   │   kyc-docs-vault, payment-proofs  │   │   IP: 192.168.31.247 (LAN)        │
│ • MongoDB Atlas (2 Clusters)  │   │ • Account 2 (Com): Pages Edge SSR,│   │ • CasaOS Linux, 15.3 GB RAM       │
│   (6,761 GeoJSON 2dsphere)    │   │   listings-media-2, properties    │   │ • Baileys WhatsApp Daemon (+91)   │
│ • Turso LibSQL Edge Archive   │   │ • Account 3 (1014): 8.8GB Media   │   │ • Local PG16 + 10TB HDD Vault     │
│   (Weekly N:1 Event Rollups)  │   │   Archive & CDN Workers           │   │   Nightly Backup at 03:30 AM IST  │
└───────────────────────────────┘   └───────────────────────────────────┘   └───────────────────────────────────┘
```

---

<div align="center">

  **Engineered with ❤️ in Pune, Maharashtra, India**  
  *BLESSIN CARE ESSENTIALS PRIVATE LIMITED*

</div>
