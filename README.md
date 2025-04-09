# 🚀 Spark Invoice Analyzer

Transforming Raw Invoices into Clean Insights with PySpark 💡

## 📊 About the Project

**Spark Invoice Analyzer** is a powerful data pipeline built in **PySpark** that extracts, transforms, and loads invoice data from a collection of unstructured JSON files into structured DataFrames.

This project showcases a complete **ETL (Extract, Transform, Load)** workflow designed for **big data processing**, focusing on:

- 🧾 Buyer & Seller information extraction  
- 🧮 Invoice and Payment normalization  
- 🛍️ Product line breakdown with dynamic handling of nested structures  
- 📦 Schema enforcement & data integrity checks  

---

## 🛠️ Tech Stack

- **PySpark** on **Google Colab**
- **JSON Data Parsing**
- **Pandas** (for comparison/debugging)
- **GitHub** for version control

---

## 📁 Data Structure

Each invoice JSON contains:
- `buyer`: Address, name, company, and country
- `seller`: VAT, address, and company name
- `invoice`: Invoice number and date
- `payment`: Total, due, discount
- `products`: List of purchased items with unit prices and quantities

All this is flattened and transformed into 5 normalized tables:
- `buyer`
- `seller`
- `invoice`
- `payment`
- `products` (with auto-generated product IDs)

---

## 🚀 Goals

- ✔️ Learn hands-on PySpark transformations
- ✔️ Practice real-world ETL logic
- ✔️ Handle nested JSON at scale
- ✔️ Build a clean, reusable data pipeline

---

## 📌 Usage

Coming soon: Jupyter Notebook + scripts to launch the full pipeline step by step.

---

## 🤝 Contributions

Feel free to fork, star ⭐ and suggest improvements via pull requests or issues!

---

## 🧠 Author

**Kacem Zelmat**  
[GitHub](https://github.com/kacemzelmat)

---

