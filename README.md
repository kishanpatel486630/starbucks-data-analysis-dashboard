# ☕ Starbucks Data Analysis Dashboard

<p align="center">
  <img src="Images/Screenshot 2026-10-06 112753.png" alt="Starbucks Data Analysis Dashboard" width="100%">
</p>

<p align="center">
  <strong>Brewing Insights. Fueling Connections.</strong><br>
  An interactive Power BI dashboard exploring Starbucks beverage nutrition, categories, caffeine, calories and product-level patterns.
</p>

<p align="center">
  <a href="#-dashboard-highlights">Dashboard Highlights</a> •
  <a href="#-key-insights">Key Insights</a> •
  <a href="#-analysis-questions">Analysis Questions</a> •
  <a href="#-project-workflow">Workflow</a> •
  <a href="#-project-files">Project Files</a>
</p>

---

## 📌 Project Overview

This project transforms Starbucks beverage data into an interactive **Power BI business intelligence dashboard**.

The dashboard is designed to make nutritional and beverage-level patterns easy to explore through KPI cards, filters, category comparisons, distribution charts and top-product analysis.

### 🎯 Main Objectives

- Understand the nutritional profile of Starbucks beverages
- Compare calories across beverage categories
- Analyze caffeine concentration by category
- Explore beverage category distribution
- Identify beverages with the highest caffeine levels
- Create an easy-to-read, business-focused dashboard

---

## 📊 Dashboard Highlights

### KPI Snapshot

| Metric | Result |
|---|---:|
| 🥤 **Total Beverages** | **33** |
| 🍬 **Average Sugar** | **33.02 g** |
| 🔥 **Average Calories** | **194.30 kcal** |
| ⚡ **Average Caffeine** | **81 mg** |

### Interactive Filters

The dashboard includes interactive controls for:

- **Protein Range**
- **Beverage Preparation**
- Category/product-level exploration

Use the filters to narrow the analysis and explore how the dashboard responds to different selections.

---

## 🔥 Key Insights

### 1. Calories vary significantly by beverage category

The dashboard shows a wide difference in average calories across beverage categories.

The highest visible average is:

> **Smoothies — 282.22 kcal**

while the lowest visible value is:

> **Coffee — 4.25 kcal**

This highlights how beverage selection can dramatically change nutritional intake.

---

### 2. Brewed Coffee leads caffeine analysis

The highest visible category in the caffeine comparison is:

> ☕ **Brewed Coffee — 294 mg**

followed by:

- **Caffè Americano — 188 mg**
- **Iced Brewed Coffee — 173 mg**
- **Caffè Mocha — 134 mg**
- **Iced Brewed Coffee — 123 mg**

This makes brewed coffee the standout category for caffeine concentration in the dashboard.

---

### 3. Average caffeine across the analyzed beverages

The overall dashboard KPI shows:

> **81 mg average caffeine**

This provides a quick benchmark for comparing individual beverages against the overall dataset.

---

### 4. Average sugar is 33.02 g

The dashboard reports:

> **33.02 g average sugar**

This KPI provides a high-level view of the sugar profile across the analyzed beverages.

---

### 5. Top caffeine beverages

The dashboard highlights the top five caffeine values:

| Rank | Beverage | Caffeine |
|---:|---|---:|
| 🥇 1 | Coffee | **294 mg** |
| 🥈 2 | Classic Espresso Drinks | **122 mg** |
| 🥉 3 | Frappuccino® Light Blended | **100 mg** |
| 4 | Frappuccino® Blended | **102 mg** |
| 5 | Shaken Iced Beverages | **99 mg** |

> The ranking above follows the values displayed in the dashboard. If the final Power BI visual uses a different product naming hierarchy, update the labels to match the final report.

---

## 💡 Business Questions Answered

<details>
<summary><strong>☕ Which beverage categories have the highest calories?</strong></summary>

The calorie comparison shows that **Smoothies** have the highest visible average calorie value at **282.22 kcal**, followed by other high-calorie categories such as Frappuccino-based beverages.
</details>

<details>
<summary><strong>⚡ Which categories are strongest in caffeine?</strong></summary>

**Brewed Coffee** is the highest visible category at **294 mg**, followed by Caffè Americano and Iced Brewed Coffee.
</details>

<details>
<summary><strong>🍬 What is the average sugar level?</strong></summary>

The dashboard reports an overall average sugar value of **33.02 g**.
</details>

<details>
<summary><strong>🔥 What is the average calorie level?</strong></summary>

The dashboard reports an overall average of **194.30 kcal**.
</details>

<details>
<summary><strong>🥤 How many beverages are included?</strong></summary>

The dashboard currently reports **33 total beverages**.
</details>

---

## 🖼️ Dashboard Preview

### Main Dashboard

<p align="center">
  <img src="Images/Screenshot 2026-10-06 112753.png" alt="Full Starbucks Power BI dashboard" width="98%">
</p>

### Dashboard Components

The dashboard combines:

```text
┌──────────────────────────────────────────────────────┐
│ ☕ Starbucks Dashboard                                │
├──────────────────────────────────────────────────────┤
│ Filters        → Protein Range / Beverage Prep       │
│                                                      │
│ KPI Cards      → Beverages / Sugar / Calories /     │
│                   Caffeine                           │
│                                                      │
│ Trend Analysis → Average Calories by Category        │
│                                                      │
│ Category View  → Beverage Category Distribution      │
│                                                      │
│ Comparison     → Average Caffeine by Category        │
│                                                      │
│ Top Products   → Top 5 Highest Caffeine Beverages   │
└──────────────────────────────────────────────────────┘
```

---

## 🧠 Analysis Approach

```mermaid
flowchart LR
    A[Raw Starbucks Data] --> B[Data Cleaning]
    B --> C[Data Transformation]
    C --> D[Exploratory Analysis]
    D --> E[KPI & Measures]
    E --> F[Power BI Visualizations]
    F --> G[Interactive Dashboard]
    G --> H[Business Insights]
```

---

## 🔄 Project Workflow

### 01 — Data Understanding
Reviewed the available beverage attributes and identified the fields needed for nutritional and category analysis.

### 02 — Data Preparation
Cleaned and prepared the dataset for consistent analysis and visualization.

### 03 — Data Analysis
Compared calories, sugar, caffeine and beverage categories.

### 04 — KPI Development
Created dashboard-level metrics for quick performance and nutritional comparisons.

### 05 — Visualization
Built interactive charts, KPI cards, category distributions and top-value comparisons in Power BI.

### 06 — Insight Generation
Converted the visual patterns into clear, easy-to-understand observations.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| 📊 **Power BI** | Dashboard & visualization |
| 🔄 **Power Query** | Data transformation |
| 📗 **Excel** | Dataset / data preparation |
| 📈 **Data Analysis** | Pattern & metric analysis |
| 🎨 **Data Visualization** | Business storytelling |

---

## 📁 Project Structure

```text
starbucks-data-analysis-dashboard/
│
├── 📂 Data/
│   └── Starbucks_Data.xlsx
│
├── 📂 Dashboard/
│   └── Starbucks_Dashboard.pbix
│
├── 📂 Images/
│   └── dashboard-preview.png
│
└── 📄 README.md
```

---

## 📥 Project Files

### 📊 Power BI Dashboard

Download and open the original Power BI report:

**[Download Starbucks_Dashboard.pbix](Dashboard/Starbucks_Dashboard.pbix)**

### 📗 Dataset

**[View / Download Starbucks Dataset](Data/Starbucks_Data.xlsx)**

> The `.pbix` file can be opened with Power BI Desktop.

---

## 🌐 Live Project Preview

### Current Version

Because the current Power BI account does not have public **Publish to web** enabled, the repository provides the complete project through:

- 🖼️ Dashboard preview
- 📊 Power BI `.pbix` file
- 📗 Dataset
- 📝 Project documentation
- 🔍 Analysis methodology

```### Future Live Version

When a public Power BI report link is available, add it here:

**[🚀 Open Interactive Dashboard](YOUR_POWER_BI_PUBLIC_LINK)**
```
---

## 📈 Skills Demonstrated

This project demonstrates practical skills in:

- Power BI dashboard development
- Data cleaning and transformation
- Exploratory data analysis
- KPI creation
- Business intelligence
- Data storytelling
- Interactive filtering
- Category comparison
- Nutritional data analysis
- Visual communication

---

## 🎓 Key Learning Outcomes

Through this project, I strengthened my ability to:

> **Turn raw data → into analysis → into visual insights → into a decision-friendly dashboard.**

The biggest focus was not only creating charts, but presenting information in a way that allows a viewer to quickly understand the dataset.

---

## 👨‍💻 About Me

### Kishan Parvadiya

**Product Designer | Data Analyst | Aspiring Product Manager**

I enjoy combining **design, data and product thinking** to build clear and useful digital experiences.

**Portfolio:**  
[🌐 Visit My Portfolio](https://new-kishan-portfolio.vercel.app/)

**GitHub:**  
[🐙 Explore My Projects](https://github.com/kishanpatel486630)

**LinkedIn:**  
[💼 Connect with Me](https://www.linkedin.com/in/kishan-parvadiya-593120268/)

---

## ⭐ If You Like This Project

If you found this project useful or interesting, consider giving the repository a ⭐.

<p align="center">
  <strong>☕ Brewing data into meaningful insights.</strong>
</p>
