# Food Prices and Wages in the Czech Republic – Power BI Project

## 📌 About the Project

The goal was to analyze the development of food prices and wages in the Czech Republic and compare the economic situation with other European countries.

## 🗂 Data Sources

The data was originally processed in SQL and exported to CSV from two final tables created during the SQL project:

- `t_jelena_puzova_project_sql_primary_final` – Contains food prices and wage indicators in the Czech Republic.
- `t_jelena_puzova_project_sql_secondary_final` – Contains macroeconomic indicators for European countries (GDP, population, etc.).

## 📄 Report Pages

### 1. **Food Prices and Wages in the Czech Republic**

This page shows the development of average wages and food prices over time in the Czech Republic. Data are displayed in Czech crowns (CZK). The user can interact using slicers to filter by food category, year, and industry.

- 📈 Line and column chart: Development of food prices and wages over time.
- 📊 Slicers for Year, Food Type, and Industry.
- 🃏 Cards: Average gross wage and average food price.
- 🍞 Bar chart: Average price by food category.

### 2. **Czech Republic in a European Context**

This page places the Czech Republic in a broader European comparison using GDP per person and average wages. The data for Czechia are still in Czech crowns (CZK), while the European GDP data are shown in euros (€) to reflect the common European economic framework.

- 🗺 Map: GDP per person in European countries.
- 🧭 Line chart: Comparison of Czech GDP and average wage over time.
- 🧱 Column chart: Average wage by industry.
- 🃏 KPI cards: Total GDP and population for Czechia.

### 3. **European Economic Overview**

This page compares GDP per person across European countries. All financial values here, including those in cards and charts, are shown in euros (€) for consistency and comparability within the European region.

- 📊 Bar chart: Average GDP per person across countries.
- 📉 Grouped column chart: Comparison of GDP per person in Western vs. Eastern Europe.
- 🔁 Slicers: Year and Country.
- 🃏 KPI cards: Average EU GDP per person and Number of countries included 

## 🔧 Features Used

- ✅ Relationships via Calendar table using `Year`
- ✅ Multiple page navigation using buttons
- ✅ Slicers (Year, Food, Country, etc.)
- ✅ Tooltips and formatted labels
- ✅ 1 calculated measure (`Average Food Units Affordable`)
- ✅ 1 calculated column (`gdp_category`)
- ✅ Custom visuals and consistent design

## 📌 Author

Jelena Puzova 
