# 📊 SuperStore Sales Dashboard

A visually interactive dashboard created using **Power BI** to analyze sales performance, profits, and trends for a fictional SuperStore. This repository contains the dataset, key insights, and objectives behind the dashboard.

---

## 🚀 Objective

The primary objective of this project is to:
1. Identify trends in **sales** and **profits** across regions, months, and categories.
2. Evaluate the impact of **ship modes**, **payment methods**, and **customer segments**.
3. Highlight top-performing products and regions to assist in decision-making.

---

## 📝 Description

The dataset used for this project is a detailed record of SuperStore transactions, including:
- **Order Details**: Order IDs, order dates, ship dates, and ship modes.
- **Customer Information**: Customer names, IDs, regions, and segments.
- **Product Details**: Categories, subcategories, and product IDs.
- **Financial Metrics**: Sales, profit, and quantity.
- **Payment Modes**: COD, cards, and online payments.
- **Shipping Details**: Shipping times and modes.

The **Power BI dashboard** visualizes this data through:
- **Line charts**: Monthly trends for sales and profits.
- **Donut charts**: Breakdown of sales by region, payment mode, and customer segment.
- **Bar charts**: Sales by category and subcategory.
- **Map visualization**: Profit and sales by state.
- **Summary Metrics**: Total orders, sales, profit, and average ship days.

---

## 📈 Key Insights

### 1. **Overall Performance**
- **Total Orders:** 22K
- **Total Sales:** $1.56M
- **Total Profit:** $175K
- **Average Ship Days:** ~10 days

### 2. **Sales by Region**
- **West:** $522K (Top-performing region)
- **Central:** $341K
- **East:** $450K
- **South:** $252K

### 3. **Profit by Month**
- Highest profits in **January** ($19.4K) and **December** ($18.7K).
- Lowest profits in **April** ($1.5K).

### 4. **Sales by Category**
- **Office Supplies:** $643K (Top category)
- **Technology:** $471K
- **Furniture:** $452K

### 5. **Top 5 Subcategories**
- **Phones:** $196K
- **Chairs:** $182K
- **Binders:** $175K
- **Storage:** $150K
- **Accessories:** $122K

### 6. **Sales by Ship Mode**
- **Standard Class:** $912K (Preferred shipping mode)
- **Same Day:** $96K (Least used)

### 7. **Sales by Payment Mode**
- **COD (Cash on Delivery):** $667K (43%)
- **Online:** $554K (35%)
- **Cards:** $344K (22%)

---

## 🛠 Tools Used

- **Power BI**: For creating and designing the dashboard.
- **Python (Pandas)**: For data cleaning and preprocessing.

---

## 📂 Dataset

The dataset (`SuperStore_Sales_Dataset.csv`) contains:
- **5,901 rows** and **23 columns** of data covering order details, financials, customer information, and more.
- Key columns include `Order ID`, `Order Date`, `Region`, `Category`, `Sub-Category`, `Sales`, `Profit`, and `Payment Mode`.

---

## 📊 Dashboard Snapshots

![Dashboard](path/to/dashboard/image.png)

---

## 💡 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/SuperStore-Sales-Dashboard.git
