# 📱 Mobile Phone Scraper

This project is a Python-based web scraper that extracts **mobile phone product data** (name, price, and availability status) from [Unique.com.mm](https://unique.com.mm/collections/mobile-phone). The extracted data is saved into an Excel file for easy analysis.

---

## 🚀 Features
- Scrapes product **names**, **prices**, and **status** (availability).
- Iterates through **all pages** automatically.
- Exports results into a **timestamped Excel file**.
- Uses **BeautifulSoup** for parsing and **pandas** for structured data handling.
- Progress tracking with **tqdm**.

---

## 📦 Requirements
Make sure you have Python 3.7+ installed. Install the required libraries:


---

## 🛠️ How It Works
1. **Extract Last Page Number**  
   The script determines how many pages of products exist.
2. **Scrape Product Data**  
   For each page, it extracts:
   - Product Name  
   - Product Price  
   - Product Status (e.g., In Stock, Low Stock, Out of Stock)
3. **Save to Excel**  
   Results are saved as `Output HH-MM-SS.xlsx` with the current time in the filename.

---

## ▶️ Usage
Run the script directly:

```bash


After completion, you’ll see:

```
All steps are completed!
```

And an Excel file will be generated in the project directory.

---

## 📂 Output Example
The Excel file will contain:

| Product Name       | Product Price | Product Status |
|--------------------|---------------|----------------|
| iPhone 14 Pro Max  | 2500000       | In Stock       |
| Samsung Galaxy S23 | 1800000       | Low Stock      |

---

## ⚠️ Notes
- This script is tailored for **Unique.com.mm** and may need adjustments if the site structure changes.
- Be mindful of scraping ethics: avoid overwhelming the server with too many requests.

---

## 📜 License
This project is licensed under the MIT License – feel free to use and modify.
