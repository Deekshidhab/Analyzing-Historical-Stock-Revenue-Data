# Tesla and GameStop Stock & Revenue Analysis

A Python data analysis project that explores historical stock prices and quarterly revenue for **Tesla (TSLA)** and **GameStop (GME)**. The project retrieves stock-price data, loads and cleans revenue data, and creates interactive visualizations with Plotly.

## Project Overview

This project demonstrates a basic financial-data analysis workflow:

- Retrieve historical stock-price data using `yfinance`.
- Load quarterly revenue data from the IBM Skills Network project data files.
- Clean revenue values by removing currency symbols and commas, converting values to numeric types, and dropping missing records.
- Visualize stock-price trends and quarterly revenue using interactive Plotly charts.
- Compare the stock-price and revenue histories of Tesla and GameStop.

## Tools and Technologies

- **Python**
- **Pandas** – data loading and cleaning
- **yfinance** – historical stock-price data
- **Requests** and **BeautifulSoup** – retrieving/parsing web content
- **Plotly** – interactive charts
- **Jupyter Notebook** – analysis environment

## Repository Structure

```text
tesla-gamestop-stock-analysis/
│
├── Tesla_GameStop_Stock_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/tesla-gamestop-stock-analysis.git
cd tesla-gamestop-stock-analysis
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install the dependencies

It is recommended to use a virtual environment.

```bash
python -m venv .venv
```

Activate it:

**Windows**
```bash
.venv\Scripts\activate
```

**macOS / Linux**
```bash
source .venv/bin/activate
```

Install the packages:

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open `Tesla_GameStop_Stock_Analysis.ipynb` and run the cells from top to bottom.

## Analysis Workflow

### Tesla
1. Download historical TSLA stock data using `yfinance`.
2. Load Tesla quarterly revenue data.
3. Clean and convert revenue values to numeric format.
4. Plot Tesla's historical closing stock price.
5. Plot Tesla's quarterly revenue.

### GameStop
1. Download historical GME stock data using `yfinance`.
2. Retrieve GameStop revenue data from the IBM Skills Network project data page.
3. Clean and convert revenue values to numeric format.
4. Plot GameStop's historical closing stock price.
5. Plot GameStop's quarterly revenue.

## Visualizations

The notebook creates four interactive charts:

1. Tesla stock price over time
2. Tesla quarterly revenue
3. GameStop stock price over time
4. GameStop quarterly revenue

## Data Sources

- **Stock prices:** Retrieved at runtime from Yahoo Finance through the `yfinance` Python library.
- **Revenue data:** IBM Skills Network project data files:
  - Tesla revenue CSV: `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/tesla_revenue.csv`
  - GameStop revenue HTML: `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html`

Data availability and the returned history can change over time. The notebook retrieves data when it is executed; results may therefore differ from one run to another.

## Key Skills Demonstrated

- Financial data retrieval
- Web data extraction
- Data cleaning and preprocessing
- Time-series exploration
- Interactive data visualization
- Python data analysis workflow

## Limitations

- This is an educational data-analysis project, not an investment recommendation.
- The stock-price history depends on the data returned by Yahoo Finance.
- Revenue data is sourced from the IBM Skills Network project files and may not represent the latest reported figures.
- The notebook focuses on descriptive analysis; it does not perform forecasting or make buy/sell recommendations.

## How to Use This Project

You can run the notebook, inspect the data-cleaning steps, interact with the charts, and adapt the workflow to analyze other publicly traded companies.

---

**Author:** DEEKSHIDHA B  
**GitHub:** https://github.com/deekshidhab

*Update the author and GitHub profile details before publishing.*
