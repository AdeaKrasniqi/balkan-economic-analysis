# Economic Indicators in the Balkans (2010–2024)

This project analyzes and visualizes three key economic indicators in Balkan countries from 2010 to 2024:
- **GDP Growth (annual %)**
- **Unemployment Rate (% of total labor force)**
- **Inflation Rate (consumer prices, annual %)**

The analysis uses Python and its data science libraries to explore trends, compare countries, and study the economic impact of COVID-19 (before, during, and after the pandemic).

---

## 📂 Project Files
- `GDP.csv` → raw GDP data  
- `Unemployment.csv` → raw unemployment data  
- `Inflation.csv` → raw inflation data  
- `Economic_Indicators_Balkans.csv` → cleaned and merged dataset (final dataset)  
- `Economic_Indicators_Balkans.ipynb` → Jupyter Notebook with full code, cleaning steps, and visualizations   

---

## ⚙️ What the code does
1. **Reads raw CSV files** (GDP, Unemployment, Inflation).  
2. **Cleans the data** by removing unnecessary columns and converting it into long format.  
3. **Merges** the three indicators into one dataset (`Economic_Indicators_Balkans.csv`).  
4. **Explores missing values and datatypes** to ensure data quality.  
5. **Visualizes**:
   - Correlation matrices (overall + per country)  
   - Line charts showing trends of GDP, Unemployment, and Inflation (2010–2024)  
   - Combined plots with min/max values per country  
   - Bar charts comparing indicators **before, during, and after COVID-19**  




   pip install pandas numpy matplotlib seaborn

