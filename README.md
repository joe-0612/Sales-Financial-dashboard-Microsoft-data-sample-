# Sales-Financial-dashboard-Microsoft-data-sample-

# 📊 Power BI Sales Financial Dashboard

This repository contains a Power BI dashboard built using the **Microsoft Financial Sample.xlsx** dataset. The dashboard provides insights into sales performance and 
profitability across multiple dimensions such as Segment, Country, and Product.

---

## ✅ Objectives

- Visualize **Total Sales** and **Total Profit**
- Enable **interactive filtering** through slicers
- Include **time-series analysis** of Sales and Profit
- Use **summary cards** for KPIs
- Apply a **consistent visual theme**
- Include **navigational elements** 
- Create a **pie chart** to visualize segment-wise sales share

---

## 📂 Contents

| File                                     | Description                             |
|------------------------------------------|-----------------------------------------|
| `Financial Sample.xlsx`                  | Dataset used for building the dashboard |
| `My Sales BI dashboard.pbix`             | Power BI dashboard file                 |
| `Screenshot (106)/`                      | Screenshots of the dashboard (optional) |
| `README.md` (Instructions included)      | This project summary and documentation  |

---

## 📊 Dashboard Features

- **KPI Cards** for:
  - Total Sales
  - Total Profit
  - Profit Margin %
  
- **Slicers/Filters** for:
  - Country
  - Segment
  - Product
  

- **Time Series Charts**:
  - Sales Over Time (Line Chart)
  - Profit Over Time (Line Chart)

- **Pie Chart**:
  - Sales by Segment (Proportional breakdown)

- **Color Theme**:
  - Applied a consistent, professional color scheme

- **Navigation Buttons** 

---

## 📎 Notes

- The **Growth %** KPI was excluded in this version.
- All visuals are interactive and adjust based on slicer selections.
- Built in **Power BI Desktop** (June 2025)

---

## 📸 Screenshots
- Screenshot (106)

---

## 🚀 How to Use

1. Clone this repository 
2. Open `My Sales BI dashboard.pbix` using Power BI Desktop
3. Explore, filter, and extend the dashboard as needed

---

## 📌 Dataset Source

- Microsoft Financial Sample: [Download Link](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)



--- Instructions--

# 🧭 Step-by-Step Instructions: Power BI Sales Dashboard (Without Growth %)

This guide walks you through the process of building a Sales Dashboard in Power BI using the **Financial Sample.xlsx** dataset.

---

## 📁 1. Import the Dataset
1. Open Power BI Desktop
2. Click **Home > Get Data > Excel**
3. Select and load `Financial Sample.xlsx`

---

## 💡 2. Create KPI Cards
Use **Card visual** for each of the following:
- Total **Sales**
- Total **Profit**
- **Profit Margin %** (Create a calculated column: `Profit Margin = Profit / Sales`)

Steps:
1. Insert > Card
2. Drag `Sales` to the **Values** field
3. Repeat for `Profit` and `Profit Margin`

---

## 📅 3. Time-Series Analysis
1. Use a **Line Chart** to plot **Sales over Date**
2. Drag `Date` to the Axis and `Sales` to Values
3. Use another *Column Chart** for **Profit over Date**
4. Drag `Date` to the Axis and `Profit` to Values

Make sure `Date` is set to **date hierarchy** (Year, Month)

---

## 🧩 4. Add Slicers/Filters for Interactivity
Add slicers for:
- `Country`
- `Segment`
- `Product`


Steps:
1. Insert > Slicer
2. Drag a categorical field to the slicer
3. Format as Dropdown or List

---

## 📊 5. Add a Pie Chart (Sales by Segment)
1. Insert > Pie Chart
2. Drag `Segment` to Legend
3. Drag `Sales` to Values

Customize colors and enable data labels for clarity.

---

## 🎨 6. Apply a Consistent Color Theme
1. Go to **View > Themes**
2. Customize according to your preferences.


## 📦 8. Save Your Work
- Save as `My Sales BI dashboard.pbix`

---

## ✅ Output Summary

Your dashboard should include:
- Cards for Sales, Profit, and Profit Margin
- Slicers for interactivity
- Line charts for Sales & Profit over time
- Pie chart for Sales by Segment
- Theme and formatting for clean presentation

---

Built by: **Joseph R Pakhuongte**

## 📧 Author

- (Joseph R Pakhuongte)
- MSc Data Science | Power BI Enthusiast

