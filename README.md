# Comparative Evaluation of Advanced Machine Learning Models in Forecasting Environmental Patterns

This repository contains a comprehensive machine learning project that compares the performance of five advanced models (Prophet, LSTM, SVR, TCN, and Transformer) in forecasting environmental parameters such as temperature, wind turbine performance, and air quality. This project explores the strengths and limitations of these models on diverse datasets, focusing on seasonal patterns, non-linear relationships, and multi-scale dependencies. The study aims to provide insights into model selection for environmental forecasting tasks, highlighting the importance of preprocessing techniques, evaluation metrics like RMSE and SHAP values, and real-world applicability in sectors like agriculture, renewable energy, and pollution control.


# Project Overview
- This study evaluates machine learning models on three distinct datasets:
- Temperature Dataset: Hourly temperature data from Central-West Brazil.
- Wind Turbine Dataset: SCADA data representing wind turbine performance.
- Air Quality Dataset: Daily pollutant concentration levels across Indian regions.

The project follows the CRISP-DM framework, emphasizing reusable pre-processing pipelines, robust model evaluation metrics, and interpretable results.



## Project Structure
- `data/`: Datasets used in the project
- `notebooks/EDA/`: Notebooks for exploratory data analysis
- `notebooks/Models/`: Notebooks for machine learning model implementation
- `src/`: Utility code for data pre-processing
- `docs/`: Project documentation including the research paper


## Models Implemented
- Prophet: Captures long-term seasonality using additive models.
- LSTM: Recurrent neural network for sequential and temporal dependencies.
- SVR: Support vector regression for non-linear relationships.
- TCN: Temporal convolutional network for hierarchical temporal patterns.
- Transformer: Attention-based model for multi-variable dependencies.


## Key Features
- Comprehensive EDA: In-depth analysis of each dataset's patterns, correlations, and challenges.
- Reusable Pre-processing Utilities: Custom functions for missing data handling, scaling, and feature engineering.
- Robust Evaluation Metrics: RMSE, SMAPE, SHAP values for feature importance, and coherence analysis.
- Insights for Real-World Applications: Forecasting for agriculture, renewable energy, and pollution control.


## Installation

1. Clone this repository:` git clone https://github.com/yourusername/Comparative_Evaluation_ML_Environmental_Forecasting.git 

2. Navigate to the project folder: cd Comparative_Evaluation_ML_Environmental_Forecasting

3. Run the Jupyter notebooks in the notebooks/ folder for EDA and model training.


## Results
- Temperature Dataset: TCN demonstrated the best performance for seasonal dependencies.
- Wind Turbine Dataset: LSTM captured short- and long-term temporal patterns effectively.
- Air Quality Dataset: Transformer excelled in modeling multi-variable interactions.

## Future Work
- Explore hybrid models combining TCN and Transformer.

- Implement automated hyperparameter tuning.

- Extend the framework to larger datasets and real-time applications.

## Contact

Author: Samarjit Chandrashekar Kabadi

Email: samarjithkabadi@gmail.com

LinkedIn: https://www.linkedin.com/in/samarjith-kabadi/


## License
MIT License

