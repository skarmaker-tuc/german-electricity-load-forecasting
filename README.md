# Feature Engineering in Time Series Forecasting
**An Empirical Study Using German Electricity Load Data**

[![Paper](https://img.shields.io/badge/Paper-ScienceOpen-blue)](https://doi.org/10.14293/PR2199.002316.v1)
[![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://www.python.org/)

This repository contains the official implementation and code for the paper **"Feature Engineering in Time Series Forecasting: An Empirical Study Using German Electricity Load Data"**.

## 📄 Abstract
Feature engineering is a crucial element in Time Series Forecasting.Features can be designed to capture how patterns, trends, and seasonalityevolve over time. The following sections introduce practical techniquesinspired by calendar information and Fourier terms: lag features, rollingand seasonal window aggregations, exponentially weighted moving averages,and temporal embeddings. It also shows common issues arising,such as data leakage, and clarifies why well-defined forecast horizons areso important. Finally, an experimental illustration using German electricityload data demonstrates the importance of Feature Engineering inforecasting performance on real-world time series. The aim is to give anintuitive and accessible overview that helps practitioners turn time seriesinto richer, more informative inputs for their forecasting models.

## 📊 Key Findings
* **Dataset:** Analyzed German electricity consumption data.
* **Methodology:** Comparative analysis of classical machine learning models with extensive feature engineering.
* **Result:** Feature engineering improved MAE and RMSE by more than 30%, showing that simple temporal features can significantly outperform a basic lag-1 regression model.

## 🚀 Installation & Usage

### Prerequisites

To run the experiments and reproduce the results, you will need:

* Python 3.x (3.8 or later recommended)
* The following Python libraries:
  * `pandas`
  * `numpy`
  * `scikit-learn`
  * `matplotlib`
  * `requests`  <!-- for downloading the OPSD dataset -->


1. Clone the repository:
   ```bash
   git clone [https://github.com/skarmaker-tuc/german-electricity-load-forecasting.git](https://github.com/skarmaker-tuc/german-electricity-load-forecasting.git)
