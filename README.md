# 💊 Pharmacy Platform

Pharmacy Platform is a full-stack web application for an online pharmacy and cosmetics store.  
It allows customers to browse products, manage their cart, place orders, upload prescriptions, and chat with pharmacists.  
Admins and pharmacists can manage inventory, track orders, and receive real-time notifications.

---

## 🚀 Tech Stack
- **Backend:** ASP.NET Core 9 (Web API, Code First EF Core)
- **Frontend:** Angular
- **Database:** SQL Server
- **Authentication:** JWT
- **Realtime:** SignalR (for chat & notifications)
- **Documentation:** Swagger (Swashbuckle) + OpenAPI

---

## 🎯 Features

### 🛒 Customer
- Browse products (medicines & cosmetics).
- Add to cart & checkout.
- Upload prescription to check availability.
- Realtime chat with pharmacist.
- Track order status.

### 👨‍⚕️ Pharmacist
- Manage prescriptions and validate medicines in stock.
- Answer customer chats.
- Manage orders and notify customers.

### 🛠 Admin
- Full dashboard for:
  - Product & category management.
  - Inventory control.
  - Orders & users management.
  - Notifications for new orders.
  - Reports & analytics.

---

## 📐 Architecture
- **3-Tier Architecture**
  - **DAL (Data Access Layer):** DbContext, Models, Repositories
  - **BLL (Business Logic Layer):** Services & Interfaces
  - **Presentation Layer:** Web API + Angular Client

---

## 📷 Screenshots (UI Examples)
*(Add screenshots of your project here once UI is ready)*

---

## ⚡ Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/)
- [Node.js + Angular CLI](https://angular.io/cli)
- [SQL Server](https://www.microsoft.com/sql-server)

### Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/pharmacy-platform.git
   cd pharmacy-platform
