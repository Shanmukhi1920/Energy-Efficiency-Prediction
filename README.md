
# Overview
The Energy Efficiency Prediction project integrates MLflow for experiment tracking and applies machine learning techniques to forecast heating and cooling loads in buildings. It emphasizes the utilization of architectural features to enhance the understanding of energy efficiency and to increase the accuracy of model predictions.

# Repository Contents
- `ENB2012_data.csv`: Dataset with architectural features and target variables.
- `notebook.ipynb`: Jupyter notebook with the project's code and analysis.
- `mlruns/`: MLflow logs and registered models.

# Methodology
- **Exploratory Data Analysis:** Involves the loading of data and conducting EDA using histograms, scatter plots, and heatmaps.
- **Feature Optimization:** Focuses on enhancing the dataset by implementing strategic feature engineering, aiming to refine and utilize the most relevant information.
- **Data Preprocessing:** Involves preprocessing of data, which includes tasks like standardizing data and splitting it into training and testing sets.
- **Model Training and Evaluation:** Involves the development and assessment of various regression models, such as Decision Trees, Random Forests, and Gradient Boosting
- **Key Feature Identification:** Conducts a thorough analysis to pinpoint and emphasize critical features impacting model predictions, like 'Relative Compactness' and 'Overall Height'.
- **Performance Assessment:** Focuses on evaluating the models based on key performance indicators, including RMSE, MAE, and R², coupled with an analysis of feature impacts.
- **Utilization of MLflow:** Employing MLflow for comprehensive experiment tracking, efficient model management, and ensuring streamlined deployment of models to production environments.

# Installation and Usage
To set up the project, clone the repository, install dependencies, and navigate to the directory. Run Jupyter Notebook to view the project:
```bash
git clone https://github.com/Shanmukhi1920/Energy_Efficiency
cd Energy_Efficiency
pip install -r requirements.txt
jupyter notebook
```
Then, open `Notebook.ipynb` in Jupyter.

- Access trained models and logs in the `mlruns/` directory.

# Key Findings
- 'Relative_Compactness' and 'Overall_height' significantly influence both heating and cooling loads.
- Models demonstrate high accuracy, with the heating load model slightly outperforming the cooling load model.

