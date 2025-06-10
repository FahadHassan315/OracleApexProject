# Oracle APEX Business Operations Dashboard

## Overview

This project is a **business operations dashboard and application** built with **Oracle APEX**. It streamlines key business functions by capturing and calculating information across modules like customer management, orders, vendors, expenses, purchases, and sales. 
The app not only stores data but actively computes and displays summary insights, helping users monitor and analyze core operations from a centralized interface.
---

## 🧩 Key Modules

- **Home/Dashboard** – Visual overview of total sales, expenses, customer count, and other KPIs
- **Orders** – Track customer orders and associated metrics
- **Vendors** – Manage vendor data and link to purchases
- **Customers** – Store and access customer records
- **Expenses** – Record and monitor business expenses
- **Purchase Orders** – Input and view purchasing activity
- **Sales Summary** – Consolidated sales reports with key calculations

---

## 🛠 Tech Stack

- **Oracle APEX**
- **Oracle Database**
- **PL/SQL**
- **CSS/JAVA**

---

## 📂 Folder Structure

oracle-apex-business-dashboard/
├── README.md
├── app_export/
│ └── my_apex_app.sql # Full Oracle APEX app export
├── database/
│ ├── schema_ddl.sql # Table and object creation scripts
│ └── sample_data.sql # Optional sample data (if included)
├── screenshots/
│ └── dashboard_view.png # UI screenshots
└── docs/
└── project_notes.pdf # Optional notes or diagrams

---

## 📥 How to Use

To run this project on your own Oracle APEX workspace:

### 1. **Import the APEX App**
- Log in to [apex.oracle.com](https://apex.oracle.com) or your Oracle APEX instance.
- Go to **App Builder > Import**.
- Upload and install the file:  
  `Oracle APex Project.sql`

### 2. **Create the Database Schema**
- Go to **SQL Workshop > SQL Scripts**.
- Upload and run:  
  `Schema Scripts.sql`  
  *(This will create all necessary tables, constraints, etc.)*


---

## 📸 Screenshots

![Dashboard View](screenshots/dashboard_view.png)
*Main dashboard showing key business metrics.*

---

## 👤 Author

Fahad Hassan  
(https://www.linkedin.com/in/fahad-hassan-0b691524a/)

---

## 📄 License

This project is provided for educational and showcase purposes. Not intended for commercial use without modification.
