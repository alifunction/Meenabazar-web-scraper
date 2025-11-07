# 🛒 MeenaBazar Online Web Scraper

This repository contains a **Python-based web scraper** designed to collect product information from **MeenaBazarOnline.com**, a major e-commerce platform in Bangladesh.

The scraper extracts product data across multiple categories using:
- ✅ Selenium (dynamic web interaction)
- ✅ Pandas (data structuring & export)
- ✅ CSV output per category

---

## 📌 Key Features

- Automatically scrapes *every product* under each category
- Extracts:
  - Product Name
  - Category Name
  - Current Price & Discount Price (if available)
  - Product Link
  - Image URL
- Auto-scrolls pages until all products are fully loaded
- Handles large DOM structures and dynamic content
- Produces **clean, structured datasets** ready for analytics

---

## 🔄 Data Collection Workflow

1. Load list of category URLs

2. Launch Selenium browser instance

3. Scroll dynamically until all products are visible

4. Extract structured product details

5. Store results in Pandas DataFrame

6. Export as CSV (one file per category)

---

## Output Structure
Data/
 ├── Fruits & Vegetables.csv
 ├── Meat & Fish.csv
 ├── Dairy & Eggs.csv
 ├── Bakery & Snacks.csv
 └── ...

---

## 🕒 Runtime Performance
- 1 hour 20 minutes for a full sweep of all categories
(Actual speed depends on network and machine performance)
- Designed for daily product updates
-Suitable for data analysis & BI dashboards

---

## PythonAnywhere Deployment & Scheduling for daily execution

This script is perfect for automated daily execution on PythonAnywhere:

1. Upload to PythonAnywhere
- Upload all project files to your PythonAnywhere account

- Ensure the directory structure is maintained

2. Create a scheduled task to run the main.ipynb file daily (Preferably at 1 AM)
