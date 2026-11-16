# 🏪 Bizora AI — Owner Operating System (OS)
> **Autonomous Retail ERP, High-Velocity POS & Real-Time Decision Intelligence Platform**

<div align="center">

[![MERN Stack Architecture](https://img.shields.io/badge/Stack-MERN%20(MongoDB%20•%20Express%20•%20React%20•%20Node.js)-10b981?style=for-the-badge&logo=mongodb&logoColor=white)](https://github.com/omkhade75/fieldproject)

[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas%20Cluster-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express-REST%20Engine-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com/)
[![React](https://img.shields.io/badge/React-v19.2-38bdf8?style=flat-square&logo=react&logoColor=white)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-v20%20LTS-22c55e?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-v5.8-3178c6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![CI Build Verification](https://github.com/omkhade75/fieldproject/actions/workflows/ci.yml/badge.svg)](https://github.com/omkhade75/fieldproject/actions/workflows/ci.yml)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-PgBouncer-4169e1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Prisma ORM](https://img.shields.io/badge/Prisma-v6.3-2d3748?style=flat-square&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![Security](https://img.shields.io/badge/Security-OWASP%20Hardened-10b981?style=flat-square&logo=shield)](https://owasp.org/)

**[Live Production Owner Portal](https://bizora-owner.onrender.com)** • **[Architecture Guide](file:///D:/projects/project-h-main/FULL_STACK_ARCHITECTURE.md)** • **[Report an Issue](https://github.com/omkhade75/fieldproject/issues)**

</div>

---

## 👥 Core Project Team & Collaborators

<div align="center">

| Team Member | Role & Ownership | GitHub & Contact |
| :--- | :--- | :--- |
| <img src="https://github.com/omkhade75.png?size=96" width="64" height="64" style="border-radius:50%;" alt="Om Khade"/><br/>**Om Khade** | **Project Creator & Lead Architect**<br/>• Core POS billing engine & sub-50ms offline sync architecture<br/>• TanStack Start & React 19 component design system<br/>• Prisma schema design, multi-tenant database partitioning<br/>• Dynamic UPI QR payment generation & double-entry ledger | [![GitHub](https://img.shields.io/badge/GitHub-omkhade75-181717?style=flat-square&logo=github)](https://github.com/omkhade75)<br/>[![Email](https://img.shields.io/badge/Email-omkhade09%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:omkhade09@gmail.com) |
| <img src="https://github.com/musmadevaishnav123-dot.png?size=96" width="64" height="64" style="border-radius:50%;" alt="Vaishnav Musmade"/><br/>**Vaishnav Musmade** | **Core Collaborator & Full-Stack Engineer**<br/>• Hyperlocal inventory stock tracking & automated FEFO expiry alerts<br/>• Doorstep OTP anti-fraud verification & dispatch logistics<br/>• Store telemetry dashboards, sales analytics & KPI charting<br/>• Database migration auditing & production stress testing | [![GitHub](https://img.shields.io/badge/GitHub-musmadevaishnav123--dot-181717?style=flat-square&logo=github)](https://github.com/musmadevaishnav123-dot)<br/>[![Collaborator](https://img.shields.io/badge/Collaborator-Active-10b981?style=flat-square)](https://github.com/omkhade75/fieldproject/settings/access) |
| <img src="https://github.com/priyanshdewan.png?size=96" width="64" height="64" style="border-radius:50%;" alt="Priyansh Dewan"/><br/>**Priyansh Dewan** | **Core Collaborator & Full-Stack Engineer**<br/>• System architecture & clean repository modularization<br/>• CI/CD pipeline automation & GitHub Actions workflow integration<br/>• Enterprise cybersecurity hardening, OWASP compliance & API contracts<br/>• Supabase realtime telemetry, error boundaries & profiling | [![GitHub](https://img.shields.io/badge/GitHub-priyanshdewan-181717?style=flat-square&logo=github)](https://github.com/priyanshdewan)<br/>[![Collaborator](https://img.shields.io/badge/Collaborator-Active-10b981?style=flat-square)](https://github.com/omkhade75/fieldproject/settings/access) |

</div>

---

## 🍃 Enterprise MERN Stack Architecture

Bizora is engineered on the industry-standard **MERN (MongoDB, Express, React, Node.js)** full-stack architecture, augmented with TypeScript and PostgreSQL for hybrid enterprise data management:

```
┌──────────────────────────────────────────────────────────────────────────────────┐
│                           MERN FULL-STACK ARCHITECTURE                           │
├─────────┬───────────────────┬────────────────────────────────────────────────────┤
│ 🍃 [M]  │ MongoDB Atlas     │ • Unstructured AI context & agent memory logs     │
│         │ Document Database │ • Cashier event streams & hardware telemetry       │
│         │                   │ • Append-only audit trails & interaction logs      │
├─────────┼───────────────────┼────────────────────────────────────────────────────┤
│ ⚡ [E]  │ Express / Nitro   │ • High-throughput REST API microservice layer      │
│         │ Server Engine     │ • JWT authentication guards & tenant isolation     │
│         │                   │ • Server-Side Rendering (SSR) & API routing        │
├─────────┼───────────────────┼────────────────────────────────────────────────────┤
│ ⚛️ [R]  │ React 19          │ • Sub-50ms reactive POS barcode checkout counter   │
│         │ Frontend Layer    │ • TanStack Router type-safe file-based navigation  │
│         │                   │ • Hardware-accelerated Recharts KPI visualizations │
├─────────┼───────────────────┼────────────────────────────────────────────────────┤
│ 🟢 [N]  │ Node.js 20 LTS    │ • Asynchronous offline transaction sync workers    │
│         │ Runtime Engine    │ • Dual-write reconciliation queue orchestrator     │
│         │                   │ • Dynamic NPCI UPI QR code cryptographic generator │
└─────────┴───────────────────┴────────────────────────────────────────────────────┘
```

---

## 📌 Executive Overview

**Bizora Owner OS** is an enterprise-grade autonomous retail operating system engineered for retail store owners, Kirana merchants, supermarket chains, and high-velocity physical counters. 

By unifying **sub-50ms offline barcode billing**, **instant zero-fee UPI QR payments**, **real-time batch inventory sync**, **double-entry financial accounting**, and **autonomous AI decision intelligence**, Bizora eliminates operational fragmentation and equips brick-and-mortar stores with modern quick-commerce grade technology.

```
┌────────────────────────────────────────────────────────────────────────┐
│                        BIZORA OWNER OPERATING SYSTEM                   │
├─────────────────────┬──────────────────────┬───────────────────────────┤
│ 🛒 High-Speed POS   │ 📦 Live Stock & OCR  │ 💰 Double-Entry Ledger    │
│ • Sub-50ms Offline  │ • Batch/Expiry Alert │ • Auto P&L & Balance Sheet│
│ • Barcode Scanner   │ • Low Stock Reorder  │ • GST Invoicing & Tax     │
│ • Dynamic UPI QR    │ • Multi-location Ops │ • Cash Register Audit     │
├─────────────────────┼──────────────────────┼───────────────────────────┤
│ 🤖 Decision AI      │ 🔐 Fraud Prevention  │ 📞 Voice Receptionist     │
│ • Dead-Stock Alerts │ • Doorstep OTP Check │ • 24/7 AI Phone Ordering  │
│ • Dynamic Pricing   │ • Zero-MDR Direct Pay│ • WhatsApp Broadcast Deep │
│ • Predictive Orders │ • Supervisor Auth    │ • Automatic Order Logging │
└─────────────────────┴──────────────────────┴───────────────────────────┘
```

---

## ✨ Core Capabilities & Engineering Highlights

### ⚡ 1. Sub-50ms Dual-Write Offline POS Counter
* **Instant Cashier Feedback**: POS transactions commit immediately to client-side indexed storage (`db.ts`), ensuring instantaneous barcode scanning response times (< 50ms) regardless of network latency.
* **Self-Healing Sync Shield**: When the internet drops, bills continue printing seamlessly. As soon as connectivity is restored, an asynchronous queue reconciles orders and commits atomic batch transactions to PostgreSQL.

### 📱 2. Zero-Fee Dynamic UPI QR Engine (0% MDR)
* **Direct Bank Settlement**: Generates compliant NPCI Dynamic UPI QR codes containing the invoice ID, exact payable amount, and merchant VPA:
  $$\text{upi://pay?pa=store.bizora@okaxis\&pn=StoreName\&am=TotalAmount\&cu=INR\&tn=InvoiceID}$$
* **Instant Reconciliation**: Customers scan with **Google Pay, PhonePe, Paytm, BHIM, or Cred** for zero-commission direct bank transfers without intermediary gateway deductions.

### 📦 3. Live Batch Inventory & Expiry Watchdog
* **Batch Tracking & FEFO**: Automated *First-Expired, First-Out* (FEFO) alerts safeguard perishable goods and FMCG products from waste.
* **Auto-Reorder Triggers**: Reorder levels dynamically recalculate based on historical sales velocity and seasonal trends.

### 📊 4. Double-Entry Accounting & Real-Time P&L
* **Automated Bookkeeping**: Every sale, refund, purchase, and operational expense immediately updates balanced debit/credit journal entries.
* **Automated Financial Statements**: Generates instant P&L, balance sheets, daily cash drawer reconciliation reports, and GST-ready invoices with zero manual ledger entry.

### 🔐 5. Cryptographic Doorstep Delivery OTP
* **Anti-Fraud Proof-of-Delivery**: Neighborhood delivery orders generate an encrypted 4-digit verification code. Delivery personnel cannot mark orders as complete without the customer's matching OTP.
* **Supervisor Emergency Override**: Includes strict audit-logged supervisor clearance for exceptional field delivery scenarios.

### 🤖 6. Autonomous Decision Intelligence & Voice AI
* **Inbound Voice Receptionist (Vapi)**: 24/7 phone answering agent that checks real-time product stock, answers customer questions, and takes phone orders autonomously.
* **WhatsApp Campaign Hub**: One-click broadcast promotions and automated PDF invoices sent straight to verified customer WhatsApp numbers.

---

## ⌨️ POS Cashier Keyboard Quick Reference

The checkout interface is optimized for rapid hardware keyboard usage without touching a mouse:

| Key Shortcut | Action | Description |
| :--- | :--- | :--- |
| <kbd>F2</kbd> | **Focus Search / Barcode** | Jumps cursor immediately to the product barcode scanner input |
| <kbd>F4</kbd> | **Customer Select** | Opens modal to search customer by phone or loyalty number |
| <kbd>F8</kbd> | **Discount / Promo** | Opens percentage or flat discount prompt on active cart |
| <kbd>F9</kbd> | **Tender Cash** | Quick-selects Cash payment mode and prompts received amount |
| <kbd>F10</kbd> | **Dynamic UPI QR** | Generates dynamic UPI QR on customer display screen |
| <kbd>Space</kbd> | **Print & Complete** | Finalizes active transaction, updates ledger, and prints bill |
| <kbd>Esc</kbd> | **Cancel / Clear** | Clears active selection or dismisses open drawer |

---

## 🛠️ Technology Stack Breakdown

| Technology | Layer | Role in Bizora |
| :--- | :--- | :--- |
| **MongoDB Atlas** 🍃 | **M**ERN Datastore | High-throughput document store for cashier audit trails & AI interaction memory |
| **Express / Nitro** ⚡ | M**E**RN Server Engine | High-throughput REST API microservice gateway & SSR routing middleware |
| **React 19** ⚛️ | ME**R**N Frontend | Sub-50ms reactive POS counter, TanStack Router type-safe pages & UI primitives |
| **Node.js 20 LTS** 🟢 | MER**N** Runtime | Asynchronous background workers, sync queues & atomic transaction reconciliation |
| **TypeScript 5.8** | Language Standard | Strict end-to-end type safety between database contracts and frontend components |
| **PostgreSQL 16** | Relational Ledger | ACID-compliant relational transactions, double-entry financial ledger & stock counts |
| **Prisma ORM 6.3** | ORM Layer | Type-safe query builder with automated multi-tenant `workspaceId` enforcement |
| **Tailwind CSS v4** | UI Styling | Modern, high-craft responsive design system with zero runtime CSS overhead |
| **Vapi AI** | Voice Telephony | Autonomous 24/7 inbound AI voice receptionist for customer stock inquiries & orders |

---

## 🚀 Quick Start & Local Setup

### 1. Prerequisites
* **Node.js**: `v20.x` LTS or higher
* **npm**: `v10.x` or higher (or `bun` / `pnpm`)
* **MongoDB**: MongoDB Atlas Cluster connection string
* **PostgreSQL**: PostgreSQL 15+ database instance (or Supabase connection string)

### 2. Clone Repository
```bash
git clone https://github.com/omkhade75/fieldproject.git
cd fieldproject
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Configure Environment Variables
Create a `.env` file in the project root:
```bash
cp .env.example .env
```

Ensure the following variables are configured:
```env
# MERN Stack - MongoDB Atlas Connection
MONGODB_URI="mongodb+srv://username:password@your-cluster.mongodb.net/bizora?retryWrites=true&w=majority"

# Relational Database - PostgreSQL (Supabase / Local)
DATABASE_URL="postgresql://postgres:password@localhost:5432/bizora_owner?schema=public"
DIRECT_URL="postgresql://postgres:password@localhost:5432/bizora_owner"

# Supabase Realtime & Auth
VITE_SUPABASE_URL="https://your-project.supabase.co"
VITE_SUPABASE_PUBLISHABLE_KEY="your-anon-key"

# AI & Voice Providers (Optional)
GEMINI_API_KEY="your-gemini-key"
GROQ_API_KEY="your-groq-key"
```

### 5. Generate Database Client
```bash
npx prisma generate
```

### 6. Start Development Server
```bash
npm run dev
```
The application will launch at `http://localhost:3000` (or `http://localhost:5173`).

### 7. Production Build
```bash
npm run build
npm run preview
```

---

## 🏛️ Application Directory Structure

```
fieldproject/
├── prisma/
│   ├── schema.prisma           # Complete PostgreSQL Prisma ORM Schema
│   └── migrations/             # Versioned schema migrations
├── public/                     # Static assets, logos, and audio alerts
├── scripts/
│   └── build.js                # Production build pipeline & asset patcher
├── src/
│   ├── components/             # Reusable UI primitives, badges, modals, drawers
│   │   ├── bizora-logo.tsx     # Vector brand typography & emblem
│   │   ├── details-drawers.tsx # 360-degree customer & product drawers
│   │   └── ui/                 # Radix UI + Tailwind component library
│   ├── lib/
│   │   ├── db.ts               # Sub-50ms offline transaction storage & queue
│   │   ├── api-client.ts       # Typed REST API client & error boundaries
│   │   ├── auth-context.tsx    # Owner role-based access control (RBAC)
│   │   ├── business-context.tsx# Multi-tenant state (products, stock, accounts)
│   │   └── server/
│   │       ├── mongodb.ts      # [M] MongoDB Atlas connection & audit logger
│   │       └── prisma.ts       # Prisma client instance with tenant isolation
│   ├── routes/                 # [R] React 19 file-based routes (TanStack Router)
│   │   ├── __root.tsx          # Master layout & root context provider
│   │   ├── _app.tsx            # Authenticated application shell & navigation
│   │   ├── _app.billing.tsx    # High-speed POS barcode scanner & checkout
│   │   ├── _app.products.tsx   # Product catalogue, batch numbers & OCR
│   │   ├── _app.inventory.tsx  # Stock levels, adjustments & stocktakes
│   │   ├── _app.sales.tsx      # Revenue analytics, AOV & growth graphs
│   │   ├── _app.expenses.tsx   # Operational expenditure & receipt capture
│   │   ├── _app.income.tsx     # Multi-channel revenue accounting
│   │   ├── _app.accounts.tsx   # Double-entry general ledger & balance sheet
│   │   ├── _app.ai-decisions.tsx # Autonomous restocking & pricing intelligence
│   │   ├── _app.logistics.tsx  # Delivery dispatch & doorstep OTP confirmation
│   │   ├── login.tsx           # Owner authentication & session gateway
│   │   └── register.tsx        # Self-serve store onboarding wizard
│   ├── main.tsx                # Client application bootstrapping
│   └── routeTree.gen.ts        # Auto-generated type-safe routing tree
├── components.json             # Shadcn-UI configuration
├── package.json                # Project dependencies & scripts
├── tsconfig.json               # TypeScript strict compilation settings
└── vite.config.ts              # [E] Express/Nitro & Vite build configuration
```

---

## 📄 License & Intellectual Property

This project is licensed under the [MIT License](LICENSE).  
Copyright © 2026 **Bizora AI / Om Khade, Vaishnav Musmade & Priyansh Dewan**. All rights reserved.
