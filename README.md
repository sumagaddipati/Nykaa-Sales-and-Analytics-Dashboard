# Nykaa-Sales-and-Analytics-Dashboard
# 💄 Nykaa Product Analytics Dashboard

An interactive Power BI dashboard analyzing Nykaa’s product listings — focusing on pricing strategy, reviews, discounts, and promotional insights.

---

## 📌 What is this?

This is a Power BI project built to explore product-level data from Nykaa using two publicly available datasets. The dashboard provides insights into product pricing tiers, discount patterns, customer reviews, and promotional offers like free gifts.

---

## ⚙️ Tools & Technologies Used

- Power BI (DAX, Power Query Editor)
- Microsoft Excel
- DAX (Data Analysis Expressions)
- Data Cleaning & Transformation
- Visual Slicers and Search-Based Navigation

---

## 📁 Dataset Sources

- [Nykaa Popular Brands – Kaggle](https://www.kaggle.com/datasets/jithinanievarghese/nykaa-popular-brands-cosmetics-beauty-products)
- [Nykaa Products 2023 – Kaggle](https://www.kaggle.com/datasets/pankajsharma127/nykaa-products-2023)

---

## 🔍 Key Features

- Categorized products into price buckets.
- Extracted clean numeric values from textual price and review fields
- Added flags for availability of **Free Gifts**
- Included slicers to filter by price range, review count, and gift offers
- Searchable product browser using images and product names

---

## 📊 Dashboard Visuals

- 📌 **Pie/Donut Chart** — % of products in each price segment  
- 📌 **Bar Chart** — Avg. discount per price bucket (Original vs Offer Price)  
- 📌 **Stacked Chart** — Free gift distribution across price buckets  
- 📌 **Card Browser** — Visual search with product image, name, and price  
- 📌 **Table View** — Full breakdown with sorting, search, and filters  

---

## 💡 Key Insights

- Most products fall under ₹500–₹999 range, showing a mid-range pricing strategy
- Free gifts are more common in higher price brackets
- Some products offer large discounts (₹1000+ off)
- Products with high review counts cluster in mid-priced ranges, indicating value preference

---

## 🧠 Learning Outcomes

- Applied real-world data cleaning using DAX and Power Query
- Used `SWITCH(TRUE())` to dynamically group price segments
- Designed user-friendly visuals with interactivity, filtering, and visual search
- Dealt with messy text data (MRP, ₹, commas, blanks, symbols)

---

## 📷 Demo Snapshot

> ![Screenshot 2025-06-23 141238](https://github.com/user-attachments/assets/08eac4cf-ddab-4e09-9ab4-a60a51a85383)
> ![Screenshot 2025-06-23 141247](https://github.com/user-attachments/assets/a6c7505a-d8be-4944-8899-8e0f9dd056c4)
![Screenshot 2025-06-23 141257](https://github.com/user-attachments/assets/74d68c47-06c9-47c1-b4c6-5106ffe7d3d4)
![Screenshot 2025-06-23 141313](https://github.com/user-attachments/assets/5bba3f08-e90e-4f63-8365-4a544ae04995)


## 🔮 Future Scope
Add brand/category segmentation

Integrate sentiment analysis from reviews (Python or Power Query)

Build dynamic pricing recommendations

Include competitor data (e.g., Purple, Sephora)

## 👨‍💻 Author
Made with ❤️ by Sumalatha Gaddipati
Feel free to fork, reuse, or contribute.


🏷️ Tags
Power BI 
E-Commerce 
Nykaa Data 
Analytics 
Price Buckets 
DAX Dashboard
---

