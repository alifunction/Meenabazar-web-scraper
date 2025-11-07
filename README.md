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

## 🔄 How It Works

```mermaid
flowchart LR
A[Load Category List] --> B[Launch Selenium WebDriver]
B --> C[Scroll Through Product Grid]
C --> D[Scrape Product Details]
D --> E[Store in Pandas DataFrame]
E --> F[Export to CSV per category]

## 🕒 Runtime Performance
- 1 hour 20 minutes for a full sweep of all categories
(Actual speed depends on network and machine performance)
- Designed for daily product updates
-Suitable for data analysis & BI dashboards

