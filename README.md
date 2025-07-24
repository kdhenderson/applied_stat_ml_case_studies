# Applied Statistical Machine Learning Case Studies

This repository contains a collection of case studies demonstrating various statistical and machine learning concepts through practical applications. Each case study includes data, analysis notebooks, and detailed reports.

## Repository Structure

```
applied_stat_ml_case_studies/
│
├── README.md                  # This file
├── requirements.txt           # Python dependencies
├── environment.yml            # Conda environment configuration
│
├── case_study_01_linear_regression_regularization_superconductor/
│   ├── data/                  # Superconductor materials dataset
│   ├── figures/               # Figures from analysis notebook
│   ├── case_study_01_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_01_analysis.html   # Rendered notebook
│   ├── case_study_01_report.tex      # LaTeX source for the report
│   └── case_study_01_report.pdf      # Compiled report
│
├── case_study_02_logistic_regression_imputation_diabetes/
│   ├── data/                  # Hospital readmission dataset
│   ├── figures/               # Figures from analysis notebook
│   ├── case_study_02_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_02_analysis.html   # Rendered notebook
│   ├── case_study_02_report.tex      # LaTeX source for the report
│   └── case_study_02_report.pdf      # Compiled report
│
├── case_study_03_naive_bayes_clustering_spam/
│   ├── data/                  # Email spam classification dataset
│   ├── figures/               # Figures from analysis notebook
│   ├── case_study_03_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_03_analysis.html   # Rendered notebook
│   ├── case_study_03_report.tex      # LaTeX source for the report
│   └── case_study_03_report.pdf      # Compiled report
│
├── case_study_04_xgboost_randomForest_bankruptcy/
│   ├── data/                  # Financial bankruptcy prediction dataset
│   ├── case_study_04_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_04_analysis.html   # Rendered notebook
│   ├── case_study_04_report.tex      # LaTeX source for the report
│   ├── case_study_04_report.pdf      # Compiled report
│   ├── requirements_cs4.txt          # Specific requirements for case study 4
│   └── bankrupcy_paper.pdf           # Reference paper
│
├── case_study_05_svm_sgd_networkTraffic/
│   ├── data/                  # Network traffic data for classification
│   ├── case_study_05_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_05_analysis.html   # Rendered notebook
│   ├── case_study_05_report.tex      # LaTeX source for the report
│   └── case_study_05_report.pdf      # Compiled report
│
└──  case_study_06_neuralNetworks_pytorch_hepmass/
    ├── data/                  # HEPMASS dataset for event classification
    ├── case_study_06_analysis.ipynb  # Jupyter notebook with analysis
    ├── case_study_06_analysis.html   # Rendered notebook
    ├── case_study_06_report.tex      # LaTeX source for the report
    └── case_study_06_report.pdf      # Compiled report

```

## Data Availability

**HEPMASS Dataset**

- The HEPMASS dataset used in case study 6 is not included in this repository due to its large size (over 2 GB).
- You can download the dataset directly from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/347/hepmass).
- After downloading, place the files (e.g., `all_train.csv.gz`, `all_test.csv.gz`) in the `case_study_06_neuralNetworks_pytorch_hepmass/data/` directory.

*For more information about the dataset, see the [HEPMASS dataset page](https://archive.ics.uci.edu/dataset/347/hepmass).*

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/kdhenderson/applied_stat_ml_case_studies.git
   ```

2. Set up the Python environment:
   ```bash
   # Using conda
   conda env create -f environment.yml
   
   # Or using pip
   pip install -r requirements.txt
   ```

## Case Studies Overview

1. **Linear Regression and Regularization**
   - Analysis of superconductor materials data
   - Implementation of L1 and L2 regularization (LASSO, Ridge and Elastic-Net regression)
   - Feature standardization and cross-validation
   - Residual diagnostics and model evaluation
   - Feature importance interpretation

2. **Logistic Regression with Imputation**
   - Analysis of diabetic and hospital readmission data
   - Handling missing data with multiple imputation techniques
   - Multiclass classification
   - Precision-recall curves and confusion matrices
   - Model performance metrics and feature importance

3. **Naive Bayes for Text Classification**
   - Email spam detection
   - Text preprocessing and feature extraction
   - Bag-of-words representation and TF-IDF weighting
   - Naive Bayes classifier implementation
   - K-means clustering for document grouping
   - Model evaluation and performance metrics

4. **Ensemble Methods: XGBoost and Random Forest**
   - Bankruptcy prediction using financial indicators
   - Comparison of ensemble methods
   - Feature importance analysis
   - Handling class imbalance
   - ROC curves and AUC evaluation
   - Hyperparameter optimization and model evaluation

5. **Support Vector Machines and Stochastic Gradient Descent**
   - Implementation of SVM with different kernel functions
   - Logistic regression with stochastic gradient descent optimization
   - Feature scaling and transformation
   - Hyperparameter tuning
   - Model evaluation and performance metrics

6. **Neural Networks with PyTorch**
   - Event classification using the HEPMASS dataset
   - Construction and training of feedforward neural networks
   - Use of PyTorch and PyTorch Lightning
   - Regularization techniques (dropout, activation functions)
   - Learning rate scheduling and optimizer selection
   - Model evaluation and generalization to independent test data

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 