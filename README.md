# 🧩 ETL Pipeline Project

---

## 🚀 Overview
This project demonstrates a complete **ETL (Extract, Transform, Load) pipeline** built using Python.  
It reads raw sales data from a CSV file, transforms it, and loads it into a PostgreSQL database.

---

## 🎯 Objective
- Extract data from CSV file
- Clean and transform the data
- Load the processed data into PostgreSQL
- Build a modular and reusable pipeline

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- PostgreSQL  
- psycopg2 / SQLAlchemy  

---

## 📂 Project Structure
etl_project
-│
-├── sales_data.csv
-├── etl_pipeline.py
-└── README.md

---

## 🏗️ Architecture

CSV File → Extract → Transform → Load → PostgreSQL


---

## 🔄 Data Flow

1. **Extract**
   - Read raw data from CSV file

2. **Transform**
   - Remove null values
   - Convert data types
   - Create derived column (`total_price`)

3. **Load**
   - Store cleaned data into PostgreSQL table

---

## ⚙️ Requirements

### ✅ Functional Requirements
- Read input CSV file  
- Clean missing/null values  
- Convert column types  
- Generate new columns  
- Load data into database  

### ✅ Non-Functional Requirements
- Scalable design  
- Modular code  
- Error handling  
- Easy maintainability  

---

## ⚙️ Setup Instructions

### 📌 1. Clone Repository
```bash
git clone https://github.com/your-username/etl-pipeline-project.git
cd etl-pipeline-project
