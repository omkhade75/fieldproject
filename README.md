<div align="center">

# 🚀 Bizora AI (OmniMind)
### **Enterprise AI Business Operating System & Decision Intelligence**

[![CI Build Verification](https://github.com/omkhade75/fieldproject/actions/workflows/ci.yml/badge.svg)](https://github.com/omkhade75/fieldproject/actions/workflows/ci.yml)
![Node.js Version](https://img.shields.io/badge/Node.js-v20-brightgreen?style=flat&logo=node.js)
![NestJS](https://img.shields.io/badge/NestJS-v10-red?style=flat&logo=nestjs)
![React](https://img.shields.io/badge/React-v18-61dafb?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-v5-blue?style=flat&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3-38bdf8?style=flat&logo=tailwindcss)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2d3748?style=flat&logo=prisma)
![License](https://img.shields.io/badge/License-MIT-purple?style=flat)

<br />

[**👑 Owner Portal**](https://bizora-owner.onrender.com) &nbsp;•&nbsp;
[**🛍️ Customer CRM**](https://bizora-customer.onrender.com) &nbsp;•&nbsp;
[**🌐 Marketing Portal**](https://bizora-web.onrender.com) &nbsp;•&nbsp;
[**⚙️ Backend Gateway**](https://bizora-backend-gtoe.onrender.com)

<br />

</div>

**Bizora AI** is an enterprise-grade, multi-tenant **AI Business Operating System (OS)** engineered for modern retail chains, supermarkets, Kirana stores, FMCG distributors, electronics, and apparel businesses. 

It eliminates traditional paper bill books, fragmented software, and expensive proprietary barcode guns by consolidating **Receipt POS Billing**, **Camera-based Barcode Scanning**, **Inventory & Expiry Control**, **Customer Khata (Credit Ledger)**, **Double-Entry Accounting**, **Automated WhatsApp Digital Invoicing (Twilio)**, **Autonomous Voice Reordering in Regional Languages (Vapi.ai)**, and **CEO/CFO Decision Intelligence (Google Gemini AI)** into a single unified platform.

---

## 🌐 Live Deployed Services

All client portals communicate with the centralized NestJS backend microservice hosted on Render:

| Service / Portal | Live URL | Core Responsibilities |
| :--- | :--- | :--- |
| **👑 Business Owner Portal** | [https://bizora-owner.onrender.com](https://bizora-owner.onrender.com) | Fast POS billing, camera barcode scanner, live sales history, customer Khata, supplier scorecard, expiry radar, P&L reports, and AI decision center. |
| **🛍️ Customer Storefront & CRM** | [https://bizora-customer.onrender.com](https://bizora-customer.onrender.com) | Customer portal for shoppers to view digital invoices, track order dispatches, manage loyalty points, check wallet balances, and provide feedback. |
| **🌐 Web Marketing Portal** | [https://bizora-web.onrender.com](https://bizora-web.onrender.com) | Public marketing landing page, feature interactive tours, SaaS pricing calculator, and enterprise self-onboarding wizard. |
| **⚙️ Centralized Backend API** | [https://bizora-backend-gtoe.onrender.com](https://bizora-backend-gtoe.onrender.com) | Production NestJS REST API Gateway (`/api/*`), managing multi-tenant schemas, authentication, background cron jobs, and AI agents. |

---

## 🎯 The Real-World Problem & The Bizora Solution

### 🔴 The Problem in Modern Retail
1. **Software & Data Fragmentation**: Shopkeepers juggle 4–6 separate disconnected tools — one app for billing, another for accounting, a desktop ledger for stock, and personal WhatsApp for receipts.
2. **Expensive Hardware Barriers**: Traditional retail setups force owners to invest \$100–\$300 in external handheld barcode scanner guns, thermal desktop units, and specialized POS machines.
3. **Language Barriers**: Most ERPs are built strictly in English. Non-English speaking shopkeepers, cashiers, and warehouse staff across Tier-2/3 Indian cities struggle with complex accounting software.
4. **Food & Perishable Waste**: Grocery and dairy stores suffer huge margin losses due to lack of batch expiry tracking and FIFO management.
5. **Credit (Udhar) Tracking Chaos**: Manual paper Khata books lead to lost receivables, delayed collections, and friction with regular customers.

### 🟢 The Bizora AI Solution
* **Unified Single Control Plane**: Seamless integration of POS, Stock Control, Khata Ledger, and P&L into a single browser/mobile tab.
* **Zero Hardware Gun Required**: Uses the standard browser `BarcodeDetector` / camera stream on any smartphone or tablet to scan EAN/UPC barcodes instantly.
* **12 Indian Regional Languages**: Full UI localization in Hindi, Marathi, Gujarati, Tamil, Telugu, Kannada, Malayalam, Bengali, Punjabi, Odia, Assamese, and English.
* **Automated WhatsApp Digital Receipts**: Invoices dispatched automatically to customer phones via the Twilio WhatsApp API, including PDF links.
* **Expiry Radar**: Batch expiration monitoring with proactive amber/red alerts before products turn unsellable.
* **Autonomous AI Agents (Gemini + Vapi)**:
  - **Gemini AI**: Acts as an in-house Virtual CEO & CFO, diagnosing anomalies, margin leaks, and forecasting demand spikes for festivals and rainy weekends.
  - **BizVoice (Vapi.ai)**: Autonomous voice calls in regional languages (Hindi & Marathi) to wholesalers to place reorders hands-free.

---

## ⚔️ Competitive Advantage

| Feature / Capability | Bizora AI | [Vyapar](https://vyaparapp.in) | [Khatabook](https://khatabook.com) | [Zoho Books](https://www.zoho.com/books) | [Odoo ERP](https://www.odoo.com) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **All-in-One Multi-Tenant OS** | ✅ Native | ❌ Billing Only | ❌ Ledger Only | ⚠️ Complex Add-ons | ⚠️ Expensive Hosting |
| **Camera Barcode Scanning (Web)**| ✅ Built-in | ❌ Hardware Only | ❌ Not Supported | ❌ Hardware Only | ⚠️ Module Required |
| **12 Indian Regional Languages** | ✅ Native | ⚠️ 4 Languages | ⚠️ 5 Languages | ❌ English Only | ❌ English Only |
| **Automated WhatsApp Dispatch** | ✅ Twilio API | ⚠️ Manual Share | ⚠️ Manual Share | ⚠️ Paid Extension | ⚠️ Paid Extension |
| **Autonomous Voice Reordering** | ✅ Vapi.ai | ❌ No | ❌ No | ❌ No | ❌ No |
| **Predictive AI Demand & Anomalies**| ✅ Gemini AI | ❌ No | ❌ No | ❌ No | ❌ No |
| **Expiry & Batch Radar (FIFO)** | ✅ Built-in | ⚠️ Basic | ❌ No | ⚠️ Add-on Required | ⚠️ Complex Setup |

---

## 💎 Key Features Breakdown

```
├── 🛒 Fast Receipt POS Billing (Camera Barcode Scanning & Thermal Print)
├── 📦 FIFO Stock & Warehouse Inventory (Low-Stock Triggers & Reorder Levels)
├── 🚨 Expiry Radar (Perishable Batch Tracking for Dairy, FMCG & Foods)
├── 📒 Customers & Khata Ledger (Digital Udhar Book with WhatsApp Reminders)
├── 📊 Double-Entry Accounting (Expenses, Income, Bank Accounts & P&L)
├── 🚚 Logistics & Dispatch Control (Shipment tracking & delivery ETAs)
├── 🤝 Supplier Hub & Purchase Orders (Wholesaler scorecards & inbound POs)
├── 🤖 Gemini AI Decision Center (Anomaly detection, demand forecast, AI Q&A)
├── 📞 BizVoice Assistant (Autonomous Hindi/Marathi reordering calls via Vapi)
└── 🌍 Multi-Language Localization (12 Indian Regional Languages with 1-click switch)
```

---

## 💳 SaaS Subscription Packages

Store workspaces can subscribe to modular tiers:

* **Starter / Kirana (Free Forever — ₹0)**:
  - Single-counter billing & thermal print support.
  - Hardware-free camera barcode scanning.
  - Up to 200 products & stock tracking.
  - 2 Languages (English & Hindi).
  - Manual WhatsApp receipt sharing.
* **Growth / Retailer (₹699 / mo or ₹6,999 / yr — Save 20%)**:
  - Unlimited POS billing & fast counter checkout.
  - Camera & hardware barcode gun support.
  - Unlimited products with FIFO batch control & Expiry Radar.
  - 12 Indian regional languages.
  - 500 Automated WhatsApp receipts / month.
  - 10 BizVoice voice calls / month.
  - 100 Gemini AI queries / month.
  - Double-entry accounting & P&L reports.
* **Enterprise Chain (₹1,999 / mo or ₹18,999 / yr)**:
  - Multi-store branch workspace management.
  - 10 Staff user accounts with role-based permissions (Cashier, Manager, Admin).
  - Unlimited automated WhatsApp receipts.
  - 100 BizVoice voice minutes / month.
  - Unlimited Gemini AI model queries.
  - Dedicated Super Admin priority support & audit trail logging.

---

## 🏛️ Monorepo Architecture & Directory Topology

```
bizora-monorepo/
├── apps/
│   ├── owner/                 # 👑 Owner Portal (React 18 + TanStack Router + Tailwind)
│   ├── customer/              # 🛍️ Customer CRM & Storefront (Shopper portal)
│   └── web/                   # 🌐 Marketing Landing & Store Registration
├── services/
│   └── backend/               # ⚙️ NestJS REST API Microservice
│       └── src/
│           ├── ai/            # Gemini AI Agents (CEO & CFO autonomous agents)
│           ├── controllers/   # REST Controllers (Auth, Products, POS, Comms, AI)
│           ├── database/      # Prisma PostgreSQL Database Module
│           ├── mongodb/       # MongoDB Atlas Telemetry & Audit Logs Module
│           └── services/      # Business logic services (Accounts, Inventory, Comms)
└── packages/
    ├── database/              # Shared Prisma Schema, Migrations & Seeds
    ├── ui/                    # Shared Design System & UI Components
    └── types/                 # Shared TypeScript Contracts & API Payloads
```

---

## ⚙️ Environment Configuration

Set these variables in your server configuration (e.g., Render Environment settings):

### 1. Database & Persistence
| Variable | Description |
| :--- | :--- |
| `DATABASE_URL` | PostgreSQL connection pool URL (e.g. Supabase Transaction Pooler, port 6543) |
| `DIRECT_URL` | PostgreSQL direct connection URL (used for running Prisma migrations, port 5432) |
| `MONGODB_URI` | MongoDB Atlas URI for telemetry, audit trails, and auto-healing error logs |

### 2. Authentication & Security
| Variable | Description |
| :--- | :--- |
| `JWT_SECRET` | Secret key used to sign access tokens |
| `JWT_REFRESH_SECRET` | Secret key used to sign refresh tokens |
| `CORS_ORIGIN` | Allowed frontend origins (e.g. `https://bizora-owner.onrender.com`) |
| `SYSTEM_ADMIN_EMAIL` | Root administrator email for super-admin governance |

### 3. Artificial Intelligence & Voice Agents
| Variable | Description |
| :--- | :--- |
| `GEMINI_API_KEY` | Google Gemini API key powering AI Decision Center, forecasting, and anomalies |
| `VAPI_AGENT_ID` | Vapi.ai assistant ID for automated Marathi/Hindi outbound reordering calls |
| `VAPI_PHONE_ID` | Vapi registered virtual phone number ID |
| `VAPI_PUBLIC_KEY` | Vapi public client key |
| `VAPI_PRIVATE_KEY` | Vapi private API key |

### 4. Communications & Notifications
| Variable | Description |
| :--- | :--- |
| `TWILIO_ACCOUNT_SID` | Twilio Account SID |
| `TWILIO_AUTH_TOKEN` | Twilio Auth Token |
| `TWILIO_WHATSAPP_SENDER` | Twilio approved WhatsApp sender number (e.g., `whatsapp:+14155238886`) |
| `OWNER_WHATSAPP_NUMBER` | Default store owner phone number for critical alerts |
| `MANAGER_WHATSAPP_NUMBER`| Store manager phone number for daily EOD reports |
| `RESEND_API_KEY` | Resend API key for transactional emails & onboarding |

---

## 🔌 Complete REST API Reference

All requests must include the header:  
`Authorization: Bearer <bizora_access_token>`

```
Authentication & Users
  POST   /api/auth/login                  # Authenticate with email & password
  POST   /api/auth/google                 # Sign in with Google Identity token
  GET    /api/auth/me                     # Active user session profile & roles
  POST   /api/auth/impersonate            # Super-admin tenant impersonation
  POST   /api/registration/register       # Register new merchant organization
  POST   /api/setup/complete              # Complete onboarding setup wizard

Products & Inventory
  GET    /api/products                    # List catalog products & stock counts
  POST   /api/products                    # Create new product / SKU
  GET    /api/products/:id                # Retrieve single product by ID
  PUT    /api/products/:id                # Update stock, price, cost, or expiry date
  DELETE /api/products/:id                # Soft-delete product
  POST   /api/products/bulk               # Bulk CSV/Excel inventory import

POS Billing & Ledger
  POST   /api/transactions                # Process POS transaction checkout
  GET    /api/transactions                # Historical sales transactions & audits
  DELETE /api/transactions                # Clear transactions (demo/admin maintenance)

Customers & Khata
  GET    /api/customers                   # List customer directory & credit balances
  POST   /api/customers                   # Register new customer
  GET    /api/customers/:id               # Customer profile, loyalty points, past bills
  PUT    /api/customers/:id               # Settle credit balance or update details
  POST   /api/customers/bulk              # Bulk customer import

Suppliers & Purchase Orders
  GET    /api/suppliers                   # Wholesaler directory & performance scores
  POST   /api/suppliers                   # Register new supplier
  GET    /api/suppliers/purchase-orders   # List purchase orders (POs)
  POST   /api/suppliers/purchase-orders   # Issue new purchase order for stock replenishment
  PUT    /api/suppliers/purchase-orders/:id # Update PO status (Draft -> Sent -> Received)

AI Decision Intelligence & Communications
  POST   /api/ai/ask                      # Query Bizora Gemini AI Model with store telemetry
  GET    /api/ai/model-status             # AI model inference health & confidence score
  GET    /api/analytics/command-center    # Aggregated store performance KPIs
  GET    /api/analytics/anomalies         # Detect cash leakage & shrinkage risks
  GET    /api/analytics/forecasting       # Demand forecasting predictions
  POST   /api/analytics/eod-report        # Generate End-of-Day business report
  POST   /api/comms/whatsapp/send         # Dispatch automated digital receipt to customer
  POST   /api/comms/vapi/call             # Trigger autonomous AI voice reorder call
  GET    /api/comms/logs                  # View communication dispatch logs
```

---

## ⚡ Local Development Setup

### 1. Prerequisites
- **Node.js** v20+ or **Bun** v1.1+
- **PostgreSQL** (or Supabase project)
- **MongoDB** (or MongoDB Atlas free cluster)

### 2. Clone Repository & Install Dependencies
```bash
git clone https://github.com/omkhade75/fieldproject.git
cd fieldproject

# Install all monorepo dependencies
npm install
```

### 3. Setup Environment Variables
```bash
cp .env.example .env
# Fill in your DATABASE_URL, DIRECT_URL, MONGODB_URI, JWT_SECRET, and GEMINI_API_KEY
```

### 4. Initialize Database
```bash
# Generate Prisma Client & compile database package
npm run build -w packages/database

# Optional: Seed sample retail store data
npm run seed -w packages/database
```

### 5. Run Development Servers
```bash
# Start backend API (Port 8000 / 3000)
npm run dev:backend

# Start Owner Portal in a new terminal (Port 5173)
npm run dev:owner

# Start Customer CRM Portal (Port 5174)
npm run dev:customer

# Start Web Marketing Portal (Port 5175)
npm run dev
```

---

## 🚀 Production Deployment (Render)

The monorepo contains pre-configured build scripts for seamless deployment on [Render](https://render.com):

* **Backend Service (`bizora-backend`)**:
  - **Build Command**: `npm run build:backend`
  - **Start Command**: `node services/backend/dist/main.js`
* **Owner Portal (`bizora-owner`)**:
  - **Build Command**: `npm run build:render:owner`
  - **Publish Directory**: `apps/owner/dist`
* **Customer Portal (`bizora-customer`)**:
  - **Build Command**: `npm run build:render:customer`
  - **Publish Directory**: `apps/customer/dist`
* **Marketing Web (`bizora-web`)**:
  - **Build Command**: `npm run build:render:web`
  - **Publish Directory**: `apps/web/dist`

---

## 📄 License
Distributed under the **MIT License**.  
© 2026 **Bizora AI** · Enterprise Decision Intelligence & Business OS. All rights reserved.
