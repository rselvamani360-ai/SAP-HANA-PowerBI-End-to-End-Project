# 🚀 SAP HANA to Power BI – End-to-End Sales Analytics Project

## 📖 Project Overview

This project demonstrates a complete end-to-end Business Intelligence workflow using SAP HANA and Microsoft Power BI.

The primary objective of this project is to understand how enterprise sales data is imported, stored, managed, analyzed, and visualized to support business decision-making.

The workflow begins with a CSV sales dataset, which is imported into SAP HANA running on Ubuntu Linux inside Oracle VirtualBox. The data is managed using SAP HANA Studio (Eclipse) and then connected to Microsoft Power BI to create an interactive sales analytics dashboard.

---

# 🏗️ End-to-End Architecture

![Architecture Diagram](Images/Architecture_Diagram.png)

---

# 🔄 Project Workflow

```text
CSV Sales Dataset
        │
        ▼
Oracle VirtualBox
(Ubuntu Linux)
        │
        ▼
SAP HANA Database
        │
        ▼
SAP HANA Studio (Eclipse)
        │
        ▼
Power BI (SAP HANA Connector)
        │
        ▼
Interactive Sales Dashboard
        │
        ▼
Business Insights & Decision Making
```

---

# 🛠️ Technologies Used

- SAP HANA Express Edition
- SAP HANA Studio (Eclipse)
- Oracle VirtualBox
- Ubuntu Linux
- Microsoft Power BI Desktop
- SQL
- CSV Dataset

---

# 📊 Dashboard Features

The Power BI dashboard provides:

- Total Sales KPI
- Average Sales KPI
- Total Customer Count
- Sales by Region
- Sales by Country
- Material Category Analysis
- Interactive Filters
- Business Performance Dashboard

---

# 💼 Business Problem

Organizations generate large volumes of sales data every day. However, raw data alone does not provide meaningful insights for business decisions.

Traditional reporting methods often require manual effort and consume significant time, making it difficult to monitor business performance effectively.

---

# ✅ Business Solution

This project demonstrates how SAP HANA and Microsoft Power BI can be integrated to transform raw sales data into interactive dashboards.

By storing data in SAP HANA and connecting it with Power BI, businesses can analyze sales performance through interactive reports and dashboards, enabling faster and more informed decision-making.

---

# 📸 Project Implementation

## 1️⃣ Ubuntu Linux Server

![Ubuntu Server](Images/Ubuntu_Server.png)

SAP HANA Express Edition is hosted on Ubuntu Linux running inside Oracle VirtualBox.

---

## 2️⃣ SAP HANA System

![SAP HANA](Images/SAP_HANA_System.png)

SAP HANA services are successfully running and managing the in-memory database.

---

## 3️⃣ Importing CSV Dataset

![CSV Import](Images/CSV_Import.png)

Sales data is imported into SAP HANA using SAP HANA Studio.

---

## 4️⃣ SAP HANA Sales Table

![SAP Table](Images/SAP_SALES_DATA_Table.png)

The imported sales records are stored and validated inside SAP HANA.

---

## 5️⃣ Power BI Connection

![Power BI Connection](Images/PowerBI_Connection.png)

Power BI is connected directly to SAP HANA using the native SAP HANA connector.

---

## 6️⃣ Interactive Dashboard

![Dashboard](Images/PowerBI_Dashboard.png)

The dashboard provides interactive business insights through KPIs, charts, maps, and filters.

---

# 📈 Business Insights

The dashboard helps users to:

- Monitor overall sales performance
- Compare sales across different regions
- Analyze country-wise sales distribution
- Evaluate material category performance
- Track customer distribution
- Support data-driven business decisions

---

# ⭐ Key Features

- End-to-End SAP HANA Integration
- Enterprise Database Management
- CSV Data Import
- SAP HANA Studio Operations
- SQL-Based Data Processing
- Power BI Dashboard Development
- Interactive Business Analytics
- Data Visualization

---

# 📂 Repository Structure

```text
SAP-HANA-PowerBI-End-to-End-Project
│
├── README.md
│
├── Images
│   ├── Architecture_Diagram.png
│   ├── Ubuntu_Server.png
│   ├── SAP_HANA_System.png
│   ├── CSV_Import.png
│   ├── SAP_SALES_DATA_Table.png
│   ├── PowerBI_Connection.png
│   └── PowerBI_Dashboard.png
│
└── Dashboard
    └── SAP_SALES_DATA.pbix
```

---

# 🎯 Skills Demonstrated

- SAP HANA
- SAP HANA Studio
- Database Management
- SQL
- Oracle VirtualBox
- Ubuntu Linux
- Microsoft Power BI
- Data Modeling
- Business Intelligence
- Data Visualization
- Dashboard Development
- Business Analytics

---

# 🚀 Future Enhancements

- Integration with live SAP ERP data
- Cloud deployment
- Advanced SQL analytics
- Real-time dashboard refresh
- Predictive analytics using machine learning

---

# 👨‍💻 Author

**Selvamani R**

MBA (HR) | SAP MM Learner | SAP HANA | Power BI | Business Intelligence | Data Analytics

---


