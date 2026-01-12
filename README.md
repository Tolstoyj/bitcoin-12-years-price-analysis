# Bitcoin 12 Years Price Analysis & Prediction Models

Comprehensive analysis and predictive modeling of Bitcoin price data from September 2014 to January 2026, featuring advanced machine learning and deep learning models.

## 📊 Dataset

**Dataset Source**: [Bitcoin 12 Years Price January 2026](https://www.kaggle.com/datasets/aiwithcagri/bitcoin-12-years-price-january-2026)

**Dataset Owner**: [HASAN ÇAĞRI GÜNGÖR](https://www.kaggle.com/aiwithcagri)

**Dataset Description**: This dataset explores Bitcoin's price evolution over the past 12 years, covering the period from its early market stages to January 2026. The analysis focuses on long-term trends, major market cycles, and periods of high volatility.

### Dataset Details
- **Date Range**: September 17, 2014 to January 10, 2026
- **Total Records**: 4,134 daily price observations
- **Features**: Date, Open, High, Low, Close, Volume

## 📓 Notebooks

### 1. Bitcoin EDA (Exploratory Data Analysis)
`bitcoin_eda.ipynb`

Comprehensive exploratory data analysis with focus on trading metrics, risk analysis, and market insights relevant to algorithmic trading strategies.

**Key Features**:
- Price evolution analysis with interactive visualizations
- Returns distribution and statistical analysis
- Volatility analysis (30-day rolling, annualized)
- Risk metrics (VaR, CVaR, Sharpe Ratio, Maximum Drawdown, Calmar Ratio)
- Technical indicators (RSI, MACD, Bollinger Bands, Moving Averages)
- Volume analysis and correlations
- Market regime detection (Bull/Bear markets)
- Seasonality analysis (monthly and weekly patterns)
- Year-over-year performance analysis
- Executive summary with key trading insights

### 2. Bitcoin Prediction Models
`bitcoin_prediction_models.ipynb`

Advanced predictive modeling comparing multiple approaches for Bitcoin price forecasting.

**Models Implemented**:

#### Statistical Models
- **ARIMA**: Auto-regressive Integrated Moving Average with parameter optimization
- **SARIMA**: Seasonal ARIMA with monthly seasonality
- **GARCH**: Generalized Autoregressive Conditional Heteroskedasticity for volatility forecasting

#### Traditional Machine Learning
- **Random Forest**: Ensemble of decision trees with feature importance analysis
- **XGBoost**: Gradient boosting with early stopping
- **LightGBM**: Fast gradient boosting framework
- **CatBoost**: Categorical boosting algorithm

#### Deep Learning Models
- **LSTM**: Long Short-Term Memory networks with multi-layer architecture
- **GRU**: Gated Recurrent Unit networks
- **Transformer**: Custom transformer encoder with multi-head attention

#### Ensemble Methods
- **Simple Blending**: Equal-weight average of all models
- **Weighted Blending**: Inverse RMSE weighted combination
- **Stacking**: Ridge meta-learner with time series cross-validation

**Evaluation Metrics**:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)
- R² Score
- Directional Accuracy

**Visualizations**:
- Training history plots for deep learning models
- Feature importance comparisons
- Prediction vs actual comparisons
- Scatter plots and residual analysis
- Comprehensive model comparison dashboards

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn plotly scipy scikit-learn statsmodels xgboost lightgbm catboost tensorflow keras
```

For GARCH model:
```bash
pip install arch
```

### Usage

1. **EDA Notebook**: Run `bitcoin_eda.ipynb` for comprehensive data exploration
2. **Prediction Models**: Run `bitcoin_prediction_models.ipynb` for model training and comparison

Both notebooks support:
- **Local Environment**: Automatically detects `bitcoin.csv` in the current directory
- **Kaggle Environment**: Automatically detects dataset at `/kaggle/input/bitcoin-12-years-price-january-2026/bitcoin.csv`

## 📈 Key Findings

1. **Ensemble methods** (Stacking, Blending) generally outperform individual models
2. **Tree-based models** (XGBoost, LightGBM) show strong performance for price prediction
3. **Deep learning models** (LSTM, GRU, Transformer) effectively capture temporal patterns
4. **Statistical models** (ARIMA, SARIMA) provide baseline but are outperformed by ML/DL models
5. **Weighted blending** leverages strengths of different model types

## 📝 Credits

**Dataset**: 
- **Owner**: [HASAN ÇAĞRI GÜNGÖR](https://www.kaggle.com/aiwithcagri)
- **Kaggle Dataset**: [Bitcoin 12 Years Price January 2026](https://www.kaggle.com/datasets/aiwithcagri/bitcoin-12-years-price-january-2026)

**Analysis & Modeling**: 
- Comprehensive EDA and predictive modeling implementation
- Professional-grade analysis suitable for algorithmic trading

## 📄 License

This project is for educational and research purposes. Please refer to the original dataset license on Kaggle.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Note**: This analysis is for educational purposes only and should not be considered as financial advice.
