# yhata-sales-app
Enterprise-grade Angular + Ionic mobile application developed for a U.S.-based client, enabling sales representatives to manage customers, create offline orders, and sync data with Microsoft Dynamics 365 (D365).
Designed for field sales teams, the app provides offline-first functionality, secure authentication, and real-time synchronization with enterprise systems — ensuring seamless operation even without internet connectivity.


# 🚗 Yhata Sales App

**Yhata Sales App** is an enterprise-grade **mobile sales management application** built using **Angular** and **Ionic Framework**, designed specifically for a **U.S.-based client**.  
The app empowers field sales representatives to manage customers, create and track sales orders (even in offline mode), and synchronize data seamlessly with **Microsoft Dynamics 365 (D365)**.

---

## 🧭 Overview

The Yhata Sales App simplifies field operations by providing sales agents with a powerful, responsive mobile solution that works both **online and offline**.  
It enables users to manage clients, create and process offline orders, view product catalogs, and sync data with **D365 services** once internet connectivity is restored.  

This internal-use app is deployed privately and used exclusively by the client’s authorized team.

---

## 👨‍💻 My Role – Lead Angular & Ionic Developer

As the **Lead Developer**, I was responsible for:

- Architecting the **frontend structure** using **Angular + Ionic**.
- Leading a team of developers to deliver the app end-to-end.
- Implementing **offline-first capabilities** with local storage and sync queues.
- Developing **dynamic forms and reusable components** for scalable UI.
- Integrating the app with **Microsoft Dynamics 365 (D365) services** for real-time data operations.
- Designing robust **API services** for order management, product catalogs, and customer profiles.
- Setting up **secure authentication** and role-based access.
- Collaborating closely with backend and business analysts to ensure smooth integration.
- Ensuring responsive design and optimized performance across Android and iOS platforms.

---

## 🧩 Core Features

- 🧾 **Offline Order Creation** – Sales reps can create, modify, and manage orders without internet connectivity.  
- ☁️ **D365 Integration** – Syncs customer and order data with **Microsoft Dynamics 365** backend.  
- 🚗 **Vehicle Connection Support** – Integrates with connected car systems for live order updates.  
- 🧍 **Customer Management** – Access and manage customer profiles and purchase histories.  
- 💰 **Product Catalog** – Browse and select from updated product listings synced with D365.  
- 🔒 **Role-Based Access Control** – Ensures secure login and user-specific data access.  
- 🌐 **Cross-Platform** – Fully functional on both Android and iOS via Ionic’s hybrid architecture.  

---

## ⚙️ Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend Framework** | Angular (v14+) |
| **Mobile Framework** | Ionic (v6) |
| **Language** | TypeScript |
| **State Management** | RxJS / BehaviorSubject |
| **Backend Services** | Microsoft Dynamics 365 (D365) |
| **API Communication** | REST APIs |
| **Offline Storage** | Ionic Storage / SQLite |
| **Authentication** | OAuth 2.0 / JWT |
| **Build & Deployment** | Capacitor / Android Studio / Xcode |
| **Version Control** | Git + GitHub / Azure DevOps |

---

## 🏗️ Folder Structure

yhata-sales-app/
│
├── src/
│ ├── app/
│ │ ├── components/ # Shared and reusable components
│ │ ├── pages/ # Application screens (Orders, Customers, Dashboard)
│ │ ├── services/ # API and D365 integration services
│ │ ├── store/ # State management and data synchronization logic
│ │ ├── guards/ # Authentication and route guards
│ │ └── app.module.ts
│ ├── assets/
│ │ └── icons/
│ ├── environments/
│ │ ├── environment.ts
│ │ └── environment.prod.ts
│ └── theme/
│ └── variables.scss
│
└── README.md

---

## 🔐 Key Integrations

- **Microsoft Dynamics 365 (D365)** – Core backend for order, product, and customer data.
- **Offline Sync Engine** – Custom module to store offline orders and auto-sync upon connectivity.
- **Secure Authentication** – Integrated with client’s OAuth2 identity provider.
- **Vehicle Interface APIs** – Enables order sync from connected car systems (specific to internal workflow).

---

## 🧱 Architecture Highlights

- **Modular Angular architecture** for scalable code maintenance.
- **Service-oriented approach** with reusable services for APIs and D365 operations.
- **Reactive programming** using RxJS for efficient state updates.
- **Offline-first pattern** implemented using local database synchronization queues.
- **Enterprise-level security** with role-based access and token-based API calls.

---

## ⚙️ Installation (Development Setup)

> ⚠️ *Note: This project is internal and requires client credentials and API access to Microsoft D365. Setup instructions below are for authorized team members only.*

```bash
# Clone repository
git clone https://github.com/yourusername/yhata-sales-app.git

# Navigate to project
cd yhata-sales-app

# Install dependencies
npm install

# Run in development mode
ionic serve

# Build for Android
ionic capacitor build android

# Build for iOS
ionic capacitor build ios
