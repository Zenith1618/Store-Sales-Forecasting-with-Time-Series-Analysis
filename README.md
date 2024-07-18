# Sales Forecasting with Time Series Analysis

This project focuses on analyzing and forecasting furniture sales by leveraging advanced time series analysis techniques. The primary goal is to capture the seasonal trends and provide accurate sales predictions to aid in business decision-making.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sales forecasting is crucial for businesses to plan inventory, manage resources, and strategize marketing efforts. This project uses historical furniture sales data to build a robust forecasting model, identifying seasonal patterns and trends. The model's predictions help in understanding future sales dynamics and making informed business decisions.

## Usage

1. Navigate to the `notebooks` directory and open the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Sales_Forecasting.ipynb` and run the cells to see the analysis and forecasting in action.

3. To preprocess data, build models, or make predictions programmatically, refer to the scripts in the `src` directory.

## Results

### Data Preprocessing
- Cleaned and prepared historical sales data.
- Handled missing values and outliers.
- Resampled data to a consistent frequency.

### Time Series Analysis
- Performed exploratory data analysis (EDA) to understand sales patterns.
- Decomposed time series data to identify trends, seasonality, and residuals.

### Model Building
- Tuned the SARIMA model parameter using GridSearch and Tree-Structured Parzen Estimator on metric of AIC(Akaike information criterion) and MSE

### Forecasting
- Generated future sales forecasts with confidence intervals.
- Visualized forecast results to demonstrate model accuracy and reliability.

### Key Findings
- Identified strong seasonal patterns in furniture sales.
- Provided actionable insights for future sales planning and inventory management.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

