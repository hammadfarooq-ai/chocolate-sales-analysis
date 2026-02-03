# Chocolate Sales Analysis

A comprehensive data analysis and visualization project for chocolate sales data, featuring data preprocessing, exploratory data analysis (EDA), and high-level visualizations.

## 📊 Project Overview

This project performs an in-depth analysis of chocolate sales data, including:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- High-level visualizations and dashboards
- Performance metrics analysis
- Temporal trend analysis

## 📁 Project Structure

```
Chocolate Sales/
│
├── data/
│   └── Chocolate Sales.csv          # Raw sales dataset
│
├── chocolate_sales_analysis.ipynb    # Main analysis notebook
│
└── README.md                         # Project documentation
```

## 📋 Dataset Information

The dataset contains the following columns:
- **Sales Person**: Name of the sales representative
- **Country**: Country where the sale was made
- **Product**: Type of chocolate product
- **Date**: Date of the transaction
- **Amount**: Revenue amount (in USD)
- **Boxes Shipped**: Number of boxes shipped

### Dataset Statistics
- **Total Records**: 3,282 transactions
- **Date Range**: January 2022 - August 2024
- **Countries**: 6 countries
- **Products**: 22 different chocolate products
- **Sales Persons**: 25 sales representatives

## 🚀 Getting Started

### Prerequisites

Make sure you have the following Python packages installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install from requirements:

```bash
pip install -r requirements.txt
```

### Running the Notebook

1. **Clone or download this repository**

2. **Navigate to the project directory**
   ```bash
   cd "Chocolate Sales"
   ```

3. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the analysis notebook**
   - Click on `chocolate_sales_analysis.ipynb`
   - Run all cells sequentially (Cell → Run All)

## 📈 Analysis Features

### 1. Data Preprocessing
- Currency format conversion ($X,XXX.XX → numeric)
- Date parsing and datetime conversion
- Derived feature creation (Year, Month, Quarter, Revenue per Box)
- Data quality checks and cleaning
- Handling missing values and invalid data

### 2. Exploratory Data Analysis (EDA)
- Dataset overview and statistics
- Top 10 analysis:
  - Products by revenue
  - Countries by revenue
  - Sales persons by revenue
- Statistical summaries
- Data quality assessments

### 3. High-Level Visualizations

#### Comprehensive Dashboard (10 Visualizations)
1. **Monthly Revenue Trend** - Time series analysis
2. **Top 10 Products by Revenue** - Horizontal bar chart
3. **Top 10 Countries by Revenue** - Horizontal bar chart
4. **Revenue by Quarter** - Quarterly breakdown
5. **Monthly Revenue Heatmap** - Year × Month matrix
6. **Boxes Shipped vs Revenue** - Scatter plot with correlation
7. **Top 10 Sales Persons** - Performance ranking
8. **Revenue Distribution** - Histogram
9. **Country Revenue Share** - Pie chart (Top 8)
10. **Product Revenue Share** - Pie chart (Top 8)

#### Additional Analysis (4 Visualizations)
1. **Total Revenue by Month** - Aggregated monthly trends
2. **Year-over-Year Comparison** - Annual performance
3. **Average Transaction Value Over Time** - Trend analysis
4. **Revenue vs Boxes Shipped Density** - Hexbin plot

#### Advanced Visualizations
- **Country-Product Performance Matrix** - Heatmap showing revenue by country-product combinations
- **Performance Metrics Analysis**:
  - Revenue per box by product
  - Transaction counts by country
  - Distribution analyses

## 📊 Key Insights

The analysis provides insights into:
- **Revenue Trends**: Monthly and yearly sales patterns
- **Product Performance**: Best-selling products and revenue per box metrics
- **Geographic Performance**: Country-wise sales distribution
- **Sales Team Performance**: Top-performing sales representatives
- **Seasonal Patterns**: Monthly and quarterly trends
- **Operational Metrics**: Box shipping efficiency and revenue correlation

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical visualizations
- **Jupyter Notebook**: Interactive development environment

## 📝 Notebook Structure

1. **Data Loading** - Import and initial inspection
2. **Data Preprocessing** - Cleaning and feature engineering
3. **High-Level EDA** - Statistical summaries and top performers
4. **High-Level Visualizations** - Comprehensive dashboards
5. **Summary Statistics** - Final insights and key metrics

## 🔍 Usage Tips

- **Run cells sequentially**: The notebook is designed to be run from top to bottom
- **Check outputs**: Review preprocessing results before proceeding to visualizations
- **Customize plots**: Modify figure sizes, colors, or styles as needed
- **Export results**: Use `plt.savefig()` to save visualizations

## 📄 License

This project is open source and available for educational and commercial purposes.

## 👤 Author

Created for chocolate sales data analysis and visualization.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📧 Contact

For questions or suggestions, please open an issue in the repository.

---

**Note**: Make sure the dataset file (`Chocolate Sales.csv`) is in the `data/` directory before running the notebook.
