# Tesla-Stock-Prediction

# Stock Price Forecasting System - Integrated ARIMA, Prophet & LSTM Models

This project delivers a comprehensive stock price forecasting solution that integrates multiple time-series models for accurate short-term and medium-term predictions. The system fetches real-time stock data from Yahoo Finance, processes it through a professional pipeline, and generates forecasts using three sophisticated modeling approaches with intuitive visualizations.

## Technical Stack & Models

### Data Processing & Visualization
- **Data Acquisition**: Real-time stock data retrieval using `yfinance`
- **Preprocessing**: Pandas-based cleaning, missing value handling, and time-series resampling
- **Feature Engineering**: Technical indicators (moving averages, volatility metrics)
- **Visualization**: Professional financial charts with Matplotlib and Seaborn

### Core Forecasting Models
1. **LSTM Neural Network**:
   - PyTorch-implemented bidirectional LSTM architecture
   - Sequence optimization (60-day historical window)
   - Adaptive learning rate (Adam optimizer) with gradient clipping
   - Early stopping to prevent overfitting

2. **ARIMA Modeling**:
   - Automatic parameter selection (p,d,q)
   - ADF stationarity testing and ACF/PACF analysis
   - Residual diagnostics and model validation
   - Robust fallback forecasting mechanism

3. **Facebook Prophet**:
   - Automatic seasonality and holiday effect modeling
   - Nonlinear trend capture with uncertainty intervals
   - Changepoint detection for structural breaks

### Model Evaluation
- **Metrics**: RMSE (Root Mean Square Error), MAE (Mean Absolute Error)
- **Validation**: Rolling time-window cross-validation
- **Benchmarking**: Comparative performance analysis

## Key Features
- Automated stock data retrieval and preprocessing
- Multi-model parallel training and forecasting
- 90-day future price projections
- Critical time-point predictions (30/60/90 days)
- Professional PDF report generation
- CSV export of prediction results
