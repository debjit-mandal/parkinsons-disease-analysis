# Parkinson's Disease Dataset Analysis

This repository contains a comprehensive analysis of the Parkinson's Disease dataset. The analysis includes various statistical, visual, and predictive modeling techniques to understand the factors associated with Parkinson's Disease.

## About the Dataset

This dataset comprises comprehensive health information for 2,105 patients diagnosed with Parkinson's Disease, each uniquely identified with IDs ranging from 3058 to 5162. The dataset includes:

- **Demographic Details**: Age, Gender, Ethnicity, Education Level
- **Lifestyle Factors**: BMI, Smoking Status, Alcohol Consumption, Physical Activity, Diet Quality, Sleep Quality
- **Medical History**: Family History of Parkinson's, Traumatic Brain Injury, Hypertension, Diabetes, Depression, Stroke
- **Clinical Measurements**: Blood Pressure, Cholesterol Levels, Triglycerides Levels
- **Cognitive and Functional Assessments**: UPDRS, MoCA, Functional Assessment
- **Symptoms**: Tremor, Rigidity, Bradykinesia, Postural Instability, Speech Problems, Sleep Disorders, Constipation
- **Diagnosis Information**: Parkinson's Disease Diagnosis

The dataset can be found in **Kaggle**: [🏥Parkinson's Disease Dataset Analysis🧠](https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis)

## Files in the Repository

- `Parkinsons_Disease_Advanced_Analysis.ipynb`: Jupyter Notebook containing the detailed analysis of the dataset.
- `parkinsons_disease_data.csv`: The dataset used for the analysis.
- `README.md`: This file providing an overview of the project.

## Analysis Overview

The analysis is divided into several sections:

1. **Data Exploration and Summary Statistics**:
    - Summary statistics for numerical features.
    - Distribution of categorical features.
    - Checking for missing values.

2. **Correlation Analysis**:
    - Correlation matrix for numerical features.
    - Heatmap visualization.

3. **Principal Component Analysis (PCA)**:
    - Dimensionality reduction and visualization using PCA.

4. **Predictive Modeling**:
    - Building and evaluating a Random Forest Classifier.
    - Feature importance analysis.
    - Hyperparameter tuning using GridSearchCV.
    - Cross-validation to ensure model robustness.

5. **Advanced Visualizations**:
    - ROC curve.
    - Precision-Recall curve.

6. **Clustering Analysis**:
    - Applying KMeans clustering to identify potential subgroups within the dataset.

## How to Use

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/debjit-mandal/parkinsons-disease-analysis.git
    cd parkinsons-disease-analysis
    ```

2. **Install Dependencies**:
    Make sure you have the required Python libraries installed. You can use `pip` to install them:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. **Open the Jupyter Notebook**:
    Launch Jupyter Notebook or JupyterLab and open the `Parkinsons_Disease_Advanced_Analysis.ipynb` file to explore the analysis.
    ```sh
    jupyter notebook Parkinsons_Disease_Advanced_Analysis.ipynb
    ```

## Results

The notebook contains detailed results of each analysis step, including:
- Descriptive statistics and distributions.
- Correlation heatmap showing relationships between features.
- PCA scatter plot for visualizing data in reduced dimensions.
- Performance metrics of the Random Forest Classifier.
- Feature importance bar plot.
- Optimized model performance after hyperparameter tuning.
- ROC and Precision-Recall curves for model evaluation.
- Clustering results visualized in PCA plot.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

The dataset is fictional and created for the purpose of this analysis project. It is inspired by real-world datasets related to Parkinson's Disease but does not contain real patient data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.