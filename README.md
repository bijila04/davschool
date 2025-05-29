# 🎓 School Management System – Finance & Tuckshop Module

This Django-based web application is a comprehensive **school financial management system** built for primary and core educational institutions. It integrates tools for handling **uniform store inventory (Tuckshop)**, managing **student payments**, tracking **income and expenditure**, and visualizing **financial health** via dashboards. 

---

## 🔑 Features

### 📦 Tuckshop (Uniform Store)
- Add, update, and view uniform stock.
- Set buying/selling prices and receive low-stock alerts.
- Record uniform sales and automatically compute revenue/profit.
- Inline and manual stock restocking functionality.
- Clerk/Admin role-based access for security.

### 💰 Financial Dashboard
- Combines revenue from:
  - Student payments (tuition, fees, etc.)
  - Uniform item sales
  - Other manually recorded income sources
- Tracks expenditures from:
  - Uniform buying costs
  - Manually recorded other expenditures
- Visual dashboard with charts:
  - Monthly Revenue
  - Monthly Expenditure
  - Net Profit

### 🧾 Student Payment Management
- Manage student payments with detailed info:
  - Amount, method, reference, and processed by
  - Invoice number auto-generated with category-based prefix
- Link payments to class levels and transaction types.
- Supports debit/credit classification for financial reports.

### ➕ Manual Revenue & Expenditure Recording
- Admins can log:
  - Additional income (e.g., grants, sponsorships)
  - Non-uniform expenditures (e.g., utilities, services)
- Entries reflected on the main dashboard.

---

## 🛡️ Access Control
- **Admin**: Full access to financial records, reports, and manual entry.
- **Clerk**: Access to stock listing and sales processing only.

---

## 💻 Tech Stack
- **Backend:** Django (Python)
- **Database:** SQLite (can be swapped with PostgreSQL)
- **Frontend:** HTML, CSS (inline and styled), with Chart.js for graphs

---

## 🚀 Setup
```bash
git clone <your-repo-url>
cd your-project
python manage.py migrate
python manage.py runserver
