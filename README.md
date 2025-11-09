# Momentum, Volatility, and Volume Factors in U.S. Stock Returns

**ISYE 4031 Final Project**  
*Industrial & Systems Engineering, Georgia Tech*

## 📊 Project Overview

This project analyzes the relationship between momentum, volatility, and volume factors in U.S. stock returns using S&P 500 data. We investigate how these three key market indicators influence stock performance and develop predictive models for return forecasting.

## 🎯 Research Objectives

1. **Momentum Analysis**: Examine how past price performance affects future returns
2. **Volatility Impact**: Study the relationship between price volatility and expected returns
3. **Volume Patterns**: Analyze trading volume as a predictor of price movements
4. **Factor Integration**: Develop multi-factor models combining all three indicators
5. **Predictive Modeling**: Build regression models for return prediction

## 📈 Methodology

### Data Collection
- **Source**: S&P 500 companies via Yahoo Finance API
- **Time Period**: 2021-2024 (4 years of daily data)
- **Variables**: Open, High, Low, Close, Volume, Adjusted Close

### Key Metrics
- **Momentum**: Price momentum indicators (moving averages, rate of change)
- **Volatility**: Historical volatility, GARCH models, rolling standard deviation
- **Volume**: Trading volume patterns, volume-weighted average price (VWAP)

### Analysis Framework
1. **Data Preprocessing**: Clean and prepare financial time series data
2. **Feature Engineering**: Calculate momentum, volatility, and volume indicators
3. **Exploratory Data Analysis**: Visualize relationships between factors
4. **Statistical Modeling**: Linear and non-linear regression analysis
5. **Model Validation**: Cross-validation and out-of-sample testing

## 🛠️ Technical Stack

- **Python 3.x**
- **Data Processing**: pandas, numpy
- **Financial Data**: yfinance, pandas-datareader
- **Analysis**: scikit-learn, statsmodels
- **Visualization**: matplotlib, seaborn, plotly
- **Web Scraping**: BeautifulSoup, requests

## 📁 Project Structure

```
Momentum-Volatility-and-Volume-Factors-in-U.S.-Stock-Returns/
├── Regression.ipynb          # Main analysis notebook
├── Project Proposal.pdf      # Project proposal document
├── README.md                 # This file
├── .gitignore               # Git ignore rules
└── requirements.txt         # Python dependencies (if created)
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install yfinance pandas numpy matplotlib seaborn scikit-learn beautifulsoup4 requests
```

### Running the Analysis
1. Clone this repository
2. Open `Regression.ipynb` in Jupyter Notebook or VS Code
3. Run cells sequentially to:
   - Scrape S&P 500 stock list
   - Download historical price data
   - Calculate momentum, volatility, and volume factors
   - Perform regression analysis
   - Generate visualizations and results

## 📊 Expected Deliverables

- **Data Analysis**: Comprehensive statistical analysis of factor relationships
- **Predictive Models**: Regression models with performance metrics
- **Visualizations**: Charts and plots showing factor correlations and trends
- **Research Findings**: Statistical significance tests and economic interpretations
- **Final Report**: Summary of methodology, results, and conclusions

## 🔬 Research Questions

1. Do momentum indicators significantly predict future stock returns?
2. How does volatility clustering affect return predictability?
3. Is trading volume a reliable indicator of price direction?
4. Which combination of factors provides the best predictive power?

## 👥 Team Collaboration

This project uses Git for version control and supports collaboration between team members using:
- **GitHub**: Central repository for code sharing
- **VS Code**: Local development environment
- **Google Colab**: Cloud-based notebook sharing (optional)

### Sync Workflow
1. Pull latest changes: `git pull origin main`
2. Make your edits in `Regression.ipynb`
3. Commit and push: 
   ```bash
   git add Regression.ipynb
   git commit -m "Your descriptive message"
   git push origin main
   ```

## 🔍 Key References

- Fama-French factor models
- Momentum strategies in equity markets
- GARCH volatility modeling
- Volume-price relationship studies
- Risk-return analysis in financial markets

## 📧 Contact

For questions about this project, please contact the team members or create an issue in this repository.

---

**Note**: This is an academic project for ISYE 4031 at Georgia Institute of Technology. All analysis is for educational purposes only and should not be considered as investment advice.
