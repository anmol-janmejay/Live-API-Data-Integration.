# World Indicators Analysis Dashboard

An interactive Power BI dashboard project that analyzes global development indicators using data from the World Bank API. The project uses Python and Jupyter notebooks to collect, clean, and transform economic, health, trade, poverty, environment, labour market, and technology indicators, then visualizes the results in Power BI.

## Dashboard Preview

![World Indicators Analysis Dashboard](screenshots/dashboard.png)


## Project Overview

This project demonstrates an end-to-end data analytics workflow:

1. Fetch data from the World Bank API.
2. Clean and transform the data using Python.
3. Export prepared datasets as CSV files.
4. Build an interactive dashboard in Power BI.
5. Analyze global trends across countries, regions, and years.

## Key Features

- World Bank API integration using Python
- Cleaned CSV datasets for multiple indicator categories
- Interactive Power BI dashboard with filters and slicers
- KPI cards for trade, GDP, forest area, health expenditure, and growth
- Country ranking tables for poverty reduction
- Regional health expenditure comparison
- Trend analysis by year
- Health indicator correlation heatmap
- Scatter plots for relationships between health, internet usage, unemployment, and life expectancy

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Requests
- Matplotlib
- Seaborn
- Power BI Desktop
- World Bank API

## Project Files

```text
.
├── API.ipynb
├── API (1).ipynb
├── API Data (1).ipynb
├── Power BI API.pbix
├── economic (1).csv
├── environment (1).csv
├── health (1).csv
├── labour_market.csv
├── poverty (1).csv
├── technology.csv
├── trade (1).csv
└── screenshots/
    └── dashboard.png
```

## Dataset Categories

- Economic activity and GDP growth
- Labour market indicators
- Trade and globalization
- Poverty and inequality
- Environmental indicators
- Health indicators
- Technology and internet usage

## How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
cd <repository-folder>
```

2. Install the required Python libraries:

```bash
pip install pandas numpy requests matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `API (1).ipynb` to fetch and prepare the data.

5. Open `Power BI API.pbix` in Power BI Desktop.

6. Refresh the data sources if needed.

## Dashboard Insights

The dashboard helps explore:

- Countries with the highest and lowest poverty reduction
- Average indicator trends across years
- Regional differences in health expenditure
- Relationship between health expenditure and life expectancy
- Correlation between different health indicators
- Internet penetration and unemployment trends
- GDP growth and trade performance

## Data Source

Data is collected from the [World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information).

## Author

Created as a data analytics and API integration project using Python and Power BI.
