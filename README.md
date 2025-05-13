# Demand Forecasting for Local Vegetable Market Using CNN LSTM

## Project Overview

Forecasting onion prices in local markets across Maharashtra using a hybrid CNN-LSTM model. Data was sourced from Agmarknet and preprocessed using Python.

## Repository Structure

```
├── Om22210564
│   ├── 1first.ipynb         # Data Acquisition
│   ├── second.ipynb         # Data Preprocessing
│   ├── third.ipynb          # Final Preprocessing
│   ├── DP_Final_Models.ipynb # Model Training and Prediction
│   ├── Zcombined1.csv       # Preprocessed Data
│   ├── model_architecture.pdf # CNN-LSTM Architecture
```

## Methodology

* **Data Acquisition:** Selenium script extracted data for 2013-2025, saving HTML files named by year.
* **Data Preprocessing:** HTML files converted to CSV, merged into `Zcombined1.csv`, cleaned, scaled, and enriched with moving averages.
* **Data Analysis:** EDA identified trends, seasonal patterns, and market-wise price differences using SMA and time-series decomposition.
* **Model Development:** CNN-LSTM model, outperforming XGBoost and ARIMA, was selected based on accuracy and stability.

## Dependencies

* Python 3.10+
* Pandas, NumPy, Matplotlib, Seaborn
* TensorFlow, XGBoost
* Selenium, ChromeDriver

## Usage

1. Clone the repo:

   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run data acquisition (1first.ipynb), preprocessing (second.ipynb, third.ipynb), and model training (DP\_Final\_Models.ipynb).

## License

MIT License

## Contact

For further information, contact Omkar.
