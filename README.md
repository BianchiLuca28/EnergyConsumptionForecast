# EnergyConsumptionForecast

This is a project for the Research Methodology course of the Master's degree in Computer Science at the University of Camerino.

## Project Overview

The primary objective of this research is to compare the performance of various machine learning models in forecasting the energy consumption of appliances in a low-energy building. By evaluating both regression and time series models, we aim to determine which approach provides the most accurate predictions and can be leveraged to ensure energy reduction and sustainability in households.

## Research Paper Summary

In this study, we utilized the "Appliances Energy Prediction Data" dataset, which includes 137 days (4.5 months) of energy consumption data recorded at 10-minute intervals. The dataset contains readings from multiple temperature and humidity sensors placed in different rooms, as well as weather data from a nearby weather station.

### Key Phases of the Research:

1. **Study Phase:** Identification of specific machine learning models for analysis.
2. **Training Phase:** Training the selected models to their optimal configurations.
3. **Analysis Phase:** Evaluation of model performance based on predefined metrics.
4. **Comparison Phase:** Comparative analysis to determine the best-performing models.

### Comparison Metrics:

To evaluate the models, we used the following metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### Models Evaluated:

- **Time Series Models:** ETS, ARIMA, SARIMA, LSTM
- **Regression Models:** Random Forest Regressor, Extra Trees Regressor, XGBoost Regressor, LightGBM Regressor

### Key Findings:

The results indicated that regression models, particularly the Random Forest and Extra Trees Regressors, performed better than time series models for this specific dataset. The time series models struggled, likely due to the short duration of the data and the absence of strong seasonal patterns.

## Repository Structure

- `dataset/`: Contains the dataset used for the analysis.
- `notebooks/`: Jupyter notebooks with the code for data preprocessing, model training, and evaluation.
- `README.md`: Project overview and instructions.

## Authors

- [Stanislav Teghipco](https://github.com/Staffilon)
- [Luca Bianchi](https://github.com/yourprofile)
- [Federico Cruciani](https://github.com/yourprofile)
- [Hector](https://github.com/yourprofile)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to thank the University of Camerino for providing the resources and support for this research.
