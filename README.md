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
├── case_study_01_linear_regression_regularization/
│   ├── data/                  # Dataset for linear regression analysis
│   ├── figures/               # Figures from analysis notebook
│   ├── case_study_01_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_01_analysis.html   # Rendered notebook
│   ├── case_study_01_report.tex      # LaTeX source for the report
│   └── case_study_01_report.pdf      # Compiled report
│
├── case_study_02_logistic_regression_imputation/
│   ├── data/                  # Dataset for logistic regression
│   ├── figures/               # Figures from analysis notebook
│   ├── case_study_02_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_02_analysis.html   # Rendered notebook
│   ├── case_study_02_report.tex      # LaTeX source for the report
│   └── case_study_02_report.pdf      # Compiled report
│
└── case_study_03_naive_bayes_spam/
    ├── data/                  # Dataset for spam detection
    ├── figures/               # Figures from analysis notebook
    ├── case_study_03_analysis.ipynb  # Jupyter notebook with analysis
│   ├── case_study_03_analysis.html   # Rendered notebook
    ├── case_study_03_report.tex      # LaTeX source for the report
    └── case_study_03_report.pdf      # Compiled report
```

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
   - Model selection and evaluation
   - Feature importance interpretation

2. **Logistic Regression with Imputation**
   - Analysis of diabetic and hospital readmission data
   - Handling missing data
   - Multiclass classification
   - Model performance metrics and feature importance

3. **Naive Bayes for Spam Detection**
   - Text classification
   - Feature engineering
   - Model evaluation

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 