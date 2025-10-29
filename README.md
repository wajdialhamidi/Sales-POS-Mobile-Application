# 💼 Sales & POS Mobile Application

## 📱 Overview
**Sales & POS Mobile Application** is an Android-based system developed for **field sales representatives** of a food products company.  
Each representative has a vehicle acting as a **mobile warehouse**, enabling them to sell directly to retail stores, issue invoices, manage stock levels, and track all sales and return operations — all in real time.

The application connects directly to the **company-provided API** for product data, pricing, and inventory management. Additionally, it includes **map-based features** to locate the nearest store for efficient route planning.

---

## 🚀 Key Features

### 👨‍💼 For Sales Representatives
- 🧾 **Sales Invoicing** — Create and issue invoices instantly for each sale.
- 🚚 **Vehicle Stock Management** — Track and manage the quantity of items in the mobile warehouse.
- 💸 **Company Price Control** — Sell products within the company’s predefined price limits.
- 🔄 **Purchase and Return Operations** — Handle product returns efficiently.
- 💰 **Cash and Credit Sales Support** — Record both types of transactions.
- 📊 **Invoice, Orders & Returns Reports** — View, filter, and sort all invoices, orders, and return transactions.
- 🗂️ **Filters & Search** — Easily filter reports by date, store, product, or transaction type.
- 📈 **Stock Overview** — Check current inventory levels in the representative’s vehicle at any time.
- 📄 **PDF Export** — Generate and export invoices, orders, and reports as PDF files for record-keeping.
- 🌐 **Real-Time API Integration** — Connects directly with the company’s API for products, pricing, and inventory updates.
- 🗺️ **Store Location Tracking** — Locate the nearest retail store on the map via API.
- 🔔 **Notifications** — Receive updates about stock, approvals, or new assignments.
- 📍 **Offline Mode Support** — Record transactions offline; syncs automatically when online.

---

### 🏢 For Company Management
- 📦 **Inventory Monitoring** — Track stock levels in each vehicle.
- 👥 **Sales Activity Tracking** — Monitor the performance and sales activity of each representative.
- 📈 **Reports & Analytics** — Access detailed reports on sales, stock movement, orders, and returns.
- 🧮 **Pricing Rules** — Ensure adherence to company pricing and promotions.

---

## 🛠️ Technologies Used
| Component | Technology |
|------------|-------------|
| **Frontend (Mobile App)** | Java (Android SDK) |
| **Networking** | Retrofit / Volley for API integration |
| **Database** | SQLite (for offline storage) |
| **Maps & Location** | Google Maps API / Location Services |
| **PDF Generation** | Android PDF libraries |
| **Authentication** | Secure login with API-based credentials |
| **Version Control** | Git & GitHub |
| **IDE** | Android Studio |

---

## ⚙️ How It Works
1. The company provides the **API endpoints** for products, pricing, inventory, stores, and transactions.
2. The **sales representative logs into the mobile app** using their credentials.
3. The app retrieves available products, stock, pricing rules, and store data from the API.
4. During field sales:
   - The representative selects a store (or finds the nearest one via map integration).
   - Creates a **sales invoice** and updates stock quantities.
   - Records any **returns or orders** as needed.
5. All reports can be **filtered, searched, and exported as PDF** for record-keeping.
6. Offline mode allows transactions to be recorded even without internet and synchronized later.

---

## 🧠 Purpose
This system is designed to **digitize field sales operations** for food distribution companies.  
It replaces paper-based invoices, order tracking, and manual stock management with a **mobile POS solution** for representatives, improving efficiency, accuracy, and reporting.

---

## 👨‍💻 My Role
I was responsible for:
- Developing the **Android application** (Java) for field representatives.
- Implementing **API integration** for products, pricing, inventory, stores, and transactions.
- Integrating **map-based store tracking** for locating nearby stores.
- Implementing **invoice, orders, returns reports with filters and PDF export**.
- Designing **user-friendly UI/UX** optimized for mobile field use.
- Managing **offline transaction recording** and automatic syncing.
- Handling **sales, returns, stock overview, and reporting**.

---

## 📸 Screenshots
*(You can add your screenshots in a `/screenshots` folder)*

| Login | Dashboard | Invoice | Reports | Map View |
|-------|------------|---------|---------|----------|
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) | ![Invoice](screenshots/invoice.png) | ![Reports](screenshots/reports.png) | ![Map](screenshots/map.png) |



⭐ *If you found this project interesting, consider giving it a star on GitHub!*
