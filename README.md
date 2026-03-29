# Autoregressive Pairs Trading System

An advanced quantitative trading system implementing autoregressive models for pairs trading strategies, based on the research paper "Rise and Fall: An Autoregressive Approach to Pairs Trading" by Bora Uyumazturk and Vasco Portilheiro.

## 🎯 Overview

This project implements a sophisticated pairs trading system that uses autoregressive models combined with convergence probability estimation and gamma thresholding to identify and execute profitable trading opportunities in correlated stock pairs.

### Key Features

- **Multiple AR Models**: Implementation of AR(1) and AR(2) autoregressive models
- **Advanced Pair Selection**: Distance-based and correlation-based pair identification
- **Monte Carlo Simulation**: Convergence probability estimation for trade timing
- **Risk Management**: Stop-loss mechanisms and position sizing
- **Comprehensive Backtesting**: Performance analysis with detailed metrics
- **Visualization**: Rich charts and performance dashboards

## 🚀 Quick Start

### Prerequisites

Ensure you have Python 3.8+ installed on your system.

### Installation

1. **Clone the repository**
```bash
git clone <url>
cd ML_PROJECT
```

2. **Create a virtual environment** (recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required packages**
```bash
pip install -r requirements.txt
```

### Required Dependencies

The `requirements.txt` file contains the following packages:
```
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
scipy>=1.7.0
jupyter>=1.0.0
notebook>=6.4.0
openpyxl>=3.0.0
```

## 📈 Results

### Performance Metrics

Based on backtesting with synthetic data:

| Model | ROI | Win Rate | Trades | Avg Duration |
|-------|-----|----------|--------|--------------|
| Baseline | 50.78% | 91% | 81 | 4.8 days |
| AR(1)+CP+GT | 105.95% | 100% | 91 | 2.8 days |
| AR(2)+CP+GT | 105.95% | 100% | 91 | 2.8 days |

## 📚 References

- Uyumazturk, B., & Portilheiro, V. "Rise and Fall: An Autoregressive Approach to Pairs Trading"

## 👨‍💻 Author

**Shashank S Shetty**
