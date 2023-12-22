
#### Overview
This project uses machine learning to predict heating and cooling loads in buildings based on architectural features.

#### Repository Contents
- `ENB2012_data.csv`: Dataset with architectural features and target variables.
- `notebook.ipynb`: Jupyter notebook with the project's code and analysis.
- `mlruns/`: MLflow logs and registered models.

#### Workflow Summary
- **Data Processing:** Data loading, cleaning, and preprocessing, including standardization and train-test split.
- **Feature Engineering:** Creation of new features and elimination of redundant ones for enhanced model accuracy.
- **Model Development:** Training and evaluation of Decision Tree, Random Forest, and Gradient Boosting Regressors using MLflow.
- **Model Analysis:** Performance metrics analysis (RMSE, MAE, R²) and feature importance studies.
- **Deployment:** Models registered in MLflow, with the best models transitioned to production.

#### Key Findings
- 'Relative_Compactness' and 'Overall_height' significantly influence both heating and cooling loads.
- Models demonstrate high accuracy, with the heating load model slightly outperforming the cooling load model.

#### Using the Project
- Install required libraries (listed in `requirements.txt`).
- Run `notebook.ipynb` to view the analysis and model training process.
- Access trained models and logs in the `mlruns/` directory.
