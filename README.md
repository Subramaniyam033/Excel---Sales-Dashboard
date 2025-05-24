This repository features an interactive **Sales Analysis Dashboard** built in **Microsoft Excel** using Power Pivot, Power Query, and advanced visualization tools. It delivers actionable insights into sales performance across categories, products, occasions, and time periods.

---

## 🔍 Dashboard Highlights

- **Total Orders:** 1,000  
- **Total Revenue:** ₹35,20,984  
- **Average Order Value:** ₹3,521  
- **Average Delivery Time:** 5.53 days

---

## 📈 Key Features

- Revenue insights by:
  - **Occasion**
  - **Product Category**
  - **City**
  - **Time (Hourly & Monthly)**
- **Top 5 Products** by Revenue
- **Top 10 Cities** by Order Volume
- Interactive filtering with **Slicers** (Date, Occasion)
- Clean and intuitive layout for easy interpretation

---

## 🛠 Built With

- **Microsoft Excel**
  - **Power Query Editor** for data cleaning and transformation
  - **Power Pivot** for data modeling and DAX measures
  - **Pivot Tables & Charts** for data visualization
  - **Slicers** for interactive filtering

---

## 🧩 Data Modeling

To ensure efficient and scalable analysis, a **data model** was created with relationships established between the following core tables:

- `Orders`  
- `Customers`  
- `Products`

### Work Done in Power Query Editor:

- Cleaned and transformed raw data (renamed columns, removed nulls, formatted dates)
- Created calculated columns (e.g., Order Month, Order Hour)
- Merged data where necessary
- Ensured consistency in keys for relationship building

### Data Relationships:

- `Orders[CustomerID]` → `Customers[CustomerID]`  
- `Orders[ProductID]` → `Products[ProductID]`  

This relational model allows for robust, cross-dimensional analysis across all reports and KPIs.

---
## 🎉 Revenue by Occasion

The dashboard highlights significant variations in revenue driven by different occasions:

### 🔝 Top-performing Occasions:
- **Anniversary:** ₹7L+  
- **Raksha Bandhan & Holi:** ₹6L+ each

### 🔻 Low-performing Occasions:
- **Diwali**  
- **Valentine's Day**

📌 *Use Case:* Inform targeted marketing campaigns aligned with high-revenue occasions.

---

## 📦 Revenue by Category

### 💰 Highest-grossing Category:
- **Colors:** ₹10L+

### 🧸 Other Strong Contributors:
- **Soft Toys** and **Sweets:** ₹7L+ each  
- **Moderate Performers:** Cake and Plants

### ❌ Underperformers:
- **Mugs**  
- **Raksha Bandhan** (as a category)

📌 *Insight:* Strong customer preference for personalized or consumable gift items.

---

## ⏰ Revenue by Hour (Order Time)

- **Revenue Peaks:** Early morning (7–9 AM) and evening (5–8 PM)  
- **Dips:** Midday (11 AM – 1 PM)

📌 *Application:* Optimize promotional timings and system readiness during peak hours.

---

## 📅 Revenue by Month

### 📈 Best-performing Months:
- **August** and **February** (likely due to festivals and Valentine's Day)

### 📉 Low-revenue Periods:
- **April to June**

📌 *Insight:* Useful for seasonal inventory planning and budget allocation.

---

## 🏆 Top 5 Products by Revenue

1. **Magnam Set (~₹1.3L)**  
2. **Quia Gift**  
3. **Dolores Gift**  
4. **Harum Pack**  
5. **Deserunt Box**

📌 *Application:* Promote these products through bundles, homepage placements, and upselling.

---

## 🌆 Top 10 Cities by Orders

### 🏙️ Top Cities:
- **Imphal**, **Dhanbad**, **Kavali**

### 📍 Other Key Contributors:
- **Haridwar**, **Bilaspur**, **North Dumdum**

📌 *Strategy:* Focus on these regions for targeted outreach and delivery optimization.

---

## 🎯 Filters & Interactivity

The dashboard includes slicers for:
- **Delivery Date**
- **Order Date**
- **Occasion**

📌 *Benefit:* Enables dynamic exploration and focused insights across timelines and categories.

---

## 💡 Recommendations

- Expand offerings and launch promotions around high-revenue occasions.
- Invest in trending categories like **Colors** and **Soft Toys**.
- Align operations with peak order hours and months.
- Focus on high-performing cities and explore mid-tier markets for growth.

---

## 📁 Use Cases

- E-commerce and gifting platform performance analysis  
- Business and marketing analytics  
- Demand forecasting and seasonal planning

---

## 🛠️ Tools & Technologies

- **Visualization Tool:** Microsoft Excel (PowerPivot, Charts, Slicers)  
- **Data Dimensions:** Time, Occasion, Category, Product, City  
- **Metrics Tracked:** Revenue, Order Count, Average Spending, Delivery Lead Time
