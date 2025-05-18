## 🔍 Project Overview

This Power BI project explores how food prices and average wages in the Czech Republic have developed over time. It also places the Czech Republic’s economy in a broader European context using GDP per person and other key indicators.

The project is based on data prepared during an SQL-based analysis. The datasets were cleaned, joined, and exported into two structured tables:

- `t_jelena_puzova_project_SQL_primary_final` – includes Czech wage and food price data.
- `t_jelena_puzova_project_SQL_secondary_final` – includes macroeconomic data (GDP, population) from European countries.

These two tables were then used in Power BI to build interactive and comparative visualizations.

---

## Key Objectives

- Analyze the availability and affordability of basic food items based on wage data.
- Compare food price growth vs. wage growth across industries.
- Investigate the relationship between GDP, wages, and food prices in the Czech Republic.
- Visualize the Czech Republic’s economic performance alongside other European countries.

---

## Data Sources

### 🇨🇿 Czech Data (Primary Table)
- **Tables used**:
  - `czechia_payroll`
  - `czechia_price`
  - Reference tables like `czechia_price_category`, `czechia_payroll_value_type`, etc.
- **Combined into**: `t_jelena_puzova_project_SQL_primary_final`

### European Data (Secondary Table)
- **Tables used**:
  - `countries`
  - `economies`
- **Combined into**: `t_jelena_puzova_project_SQL_secondary_final`

---

## Pages Overview

### **Page 1: Food Prices and Wages in Czechia**
- Timeline of food prices and average gross wages.
- KPI: Latest average wage and affordability of key food items (e.g., bread, milk).
- Slicers: Product type, year, industry.

### **Page 2: Czech Republic in a European Context**
- Map of GDP per person across Europe.
- KPI: Czech GDP per person and population (latest year).
- Line chart: GDP per person vs. average wage over time.
- Column chart: Average wage by industry in Czechia.

### **Page 3: European Economic Overview**
- KPI and bar chart showing GDP categories (low, medium, high).
- Comparison of population and GDP per person across selected countries.

---

## Project Requirements Fulfilled

✅ 2+ tables merged  
✅ 5+ different visuals used (cards, line chart, map, pie/bar charts, slicers)  
✅ Interactive elements (slicers and navigation)  
✅ 1 measure & 1 calculated column  
✅ Visual formatting applied  

---

## Tools Used

- Power BI Desktop
- PostgreSQL (for data preparation)
- Excel / CSV files
- GitHub (for version control and documentation)

---

## Author

**Jelena Půžová**  
