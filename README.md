# 🛍️ Vrinda Store – 2022 Sales Analysis (Excel Dashboard)

An end-to-end data analysis project in **Microsoft Excel**: data cleaning, pivot tables, pivot charts, and an interactive dashboard with slicers, built to understand Vrinda Store's 2022 sales performance.

---

## 📌 Project Overview

Vrinda Store is an Indian online fashion retailer selling ethnic and western wear across multiple e-commerce platforms. This project analyzes a full year of order data (Jan–Dec 2022) to answer:

- How did sales and orders trend month by month?
- Who is buying: men or women, and which age groups?
- Which states, channels, and categories drive the most revenue?
- How many orders are lost to returns, cancellations, and refunds?

## 📂 Repository Structure

```
├── Vrinda_Store_Data_Analysis.xlsx   # Cleaned data, pivot tables, charts & dashboard
├── dashboard.png                     # Screenshot of the final dashboard
└── README.md
```

## 🗃️ Dataset

| Field | Description |
|---|---|
| Order ID, Cust ID | Order and customer identifiers |
| Gender, Age, Age Groups | Customer demographics (Teenager <25, Adult 25–49, Senior 50+) |
| Date, Month | Order date and derived month |
| Status | Delivered / Returned / Cancelled / Refunded |
| Channel | Amazon, Myntra, Flipkart, Ajio, Nalli, Meesho, Others |
| SKU, Category, Size, Qty | Product details |
| Amount, currency | Order value (INR) |
| ship-city, ship-state, ship-postal-code, ship-country | Delivery location |
| B2B | Business order flag |

**Size:** 31,047 order lines · 21 columns · Jan 4 – Dec 6, 2022

## 🛠️ Tools & Techniques

- **Microsoft Excel**
- Data cleaning (duplicates, formatting, consistency checks)
- Calculated columns using `IF` and `TEXT` formulas (Age Groups, Month)
- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- Dashboard design

## 📊 Key Metrics

| Metric | Value |
|---|---|
| **Total Sales** | ₹2.12 Cr (₹21,176,377) |
| **Order lines** | 31,047 |
| **Units sold** | 31,237 |
| **Avg. order value** | ~₹682 |
| **States covered** | 50 |

## 🔍 Key Insights

### 1. Sales vs Orders (Monthly Trend)
- Sales peaked in **March** (₹19.3L, 2,819 orders), with a strong Q1.
- A steady decline followed, with the lowest months in **Nov–Dec** (~₹16.2L). That is about 16% below the March peak.
- Orders and sales move together, so revenue is driven by volume rather than price.

### 2. Men vs Women
- **Women generate 64% of sales** (₹13.56L vs ₹7.61L) and 69% of orders.
- Men spend more per order (~₹802 vs ~₹629).

### 3. Order Status
- **92% of orders were delivered**, worth 93% of revenue.
- Returns (3.4%), cancellations (2.7%) and refunds (1.7%) leak about **7% of order value**.

### 4. Top States
- **Maharashtra (₹29.9L), Karnataka (₹26.5L), Uttar Pradesh (₹21.0L)** lead, followed by Telangana and Tamil Nadu.
- The top 3 states contribute about 36% of sales.

### 5. Age Group vs Gender
- **Adults (25–49) are the core segment**, with 63% of sales. Seniors (50+) bring 20% and Teenagers (under 25) bring 17%.
- Women lead in every age group. **Adult women** are the largest segment (₹8.5L).

### 6. Sales Channels
- **Amazon: 35.5%**, Myntra: 23.3%, Flipkart: 21.6%. These three channels give about 80% of revenue.
- Ajio, Nalli, Meesho and others contribute 4–6% each.

### Additional Findings
- **Categories:** *Set* (₹10.5L) and *Kurta* (₹4.96L) lead, and Set alone is about 50% of sales.
- **Sizes:** M, L and XL are the best sellers.
- **B2B** orders are under 1% of sales.

## 💡 Recommendations

1. Target marketing at **adult women** in **Maharashtra, Karnataka and Uttar Pradesh**.
2. Run campaigns and new launches in **H2** to counter the sales decline.
3. Cut returns and cancellations (~7% of order value) with better size guides and product descriptions.
4. Prioritize inventory of **Sets and Kurtas** in sizes **M, L, XL**.
5. Reduce reliance on the top 3 channels by growing Ajio and Meesho.

## 🖼️ Dashboard Preview

<img width="1254" height="452" alt="000-1" src="https://github.com/user-attachments/assets/1b09385b-b06b-4f33-b847-37e816b9b527" />


## 📝 Notes

- "Orders" refers to order lines. Some Order IDs appear on multiple rows because orders can contain several items (28,471 unique Order IDs).
- The dashboard uses slicers, so open the `.xlsx` in desktop Excel for full interactivity.

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Vrinda_Store_Data_Analysis.xlsx` in Microsoft Excel.
3. Go to the **Vrinda store Report** sheet to explore the dashboard.
4. Use the slicers to filter by month, channel, and more.

## 👤 Author

**Your Name**
[LinkedIn](https://www.linkedin.com/in/akshay-nag-459298300/) · [GitHub](https://github.com/AkshaySan0)

---
⭐ If you found this project useful, feel free to star the repo!
