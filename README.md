
# Overview
The Energy Efficiency Prediction project uses MLflow and machine learning to forecast building energy loads based on architectural features. This addresses real-world needs by optimizing HVAC operations, guiding sustainable design, supporting efficient urban planning, and facilitating targeted retrofits. By combining architectural analysis with predictive modeling, the project offers a powerful tool to reduce energy consumption, costs, and environmental impact in the built environment, helping tackle climate change and resource scarcity challenges.

# Repository Contents
- `data/ENB2012_data.csv`: Dataset with architectural features and target variables.
- `notebooks/Notebook.ipynb`: Jupyter notebook with the project's code and analysis.
- `mlruns/`: MLflow logs and registered models.

# Methodology
- **Exploratory Data Analysis:** Involves the loading of data and conducting EDA using histograms, scatter plots, and heatmaps.
- **Feature Optimization:** Focuses on enhancing the dataset by implementing strategic feature engineering, aiming to refine and utilize the most relevant information.
- **Data Preprocessing:** Involves preprocessing of data, which includes tasks like standardizing data and splitting it into training and testing sets.
- **Model Training and Evaluation:** Involves the development and assessment of various regression models, such as Decision Trees, Random Forests, and Gradient Boosting
- **Key Feature Identification:** Conducts a thorough analysis to pinpoint and emphasize critical features impacting model predictions, like 'Relative Compactness' and 'Overall Height'.
- **Performance Assessment:** Focuses on evaluating the models based on key performance indicators, including RMSE, MAE, and R².
- **Utilization of MLflow:** Employing MLflow for comprehensive experiment tracking, efficient model management, and ensuring streamlined deployment of models to production environments.

# Installation and Usage
To set up the project, clone the repository, install dependencies, and navigate to the directory. Run Jupyter Notebook to view the project:
```bash
git clone https://github.com/Shanmukhi1920/Energy_Efficiency
cd Energy_Efficiency
pip install -r requirements.txt
jupyter notebook
```
Then, open `Notebook.ipynb` in Jupyter in the `notebooks/` directory.

- Access trained models and logs in the `mlruns/` directory.

# Key Findings
**Model Performance Overview**: The Gradient Boosting model exhibits strong performance and generalization for both heating (HL) and cooling load (CL) predictions, with R-squared values near 1.0 across all datasets, indicating nearly perfect fit and prediction accuracy.

**Heating Load Predictions**: Heating load predictions are highly accurate with a training RMSE of 0.27, validation RMSE of 0.45, and test RMSE of 0.427, demonstrating the model's precise fit and consistent performance across different data sets.

**Cooling Load Predictions**: Cooling load predictions, while accurate, show slightly higher errors with a training RMSE of 0.39, validation RMSE of 0.97, and test RMSE of 0.786, indicating a need for further refinement to achieve the precision seen in heating load predictions.

**Consistency and Robustness**: The model demonstrates robustness and consistency, with test R-squared values of 0.998 for HL and 0.993 for CL, suggesting strong predictive capabilities and reliability for practical applications.

# Citations
Tsanas,Athanasios and Xifara,Angeliki. (2012). Energy Efficiency. UCI Machine Learning Repository. https://doi.org/10.24432/C51307.



