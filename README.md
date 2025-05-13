# ML-Powered ADHD Predictor: Sex-Specific Differences in Brain Activity Patterns

## WiDS Datathon 2025 Project
```
![Brain Connectivity]
![ADHD]
![Sex Differences]
```
## Project Overview

This repository contains my dissertation project for the Women in Data Science (WiDS) Datathon 2025 challenge. The project focuses on developing machine learning models to predict ADHD diagnosis and biological sex using functional brain imaging data of children and adolescents, along with their socio-demographic, emotional, and parenting information.

### Research Question

> "What brain activity patterns are associated with ADHD; are they different between males and females, and, if so, how?"

The analysis provides insights into sex-specific differences in ADHD manifestation, which could improve diagnosis accuracy, especially in females who are often underdiagnosed due to presenting more inattentive symptoms.

## Dataset

This project uses data from the Healthy Brain Network (HBN), the signature scientific initiative of the Child Mind Institute. The dataset includes:

1. **Functional MRI Connectome Matrices**: Brain connectivity data showing correlations between different brain regions
2. **Categorical Metadata**: Socio-demographic information (e.g., handedness, parent's education)
3. **Quantitative Metadata**: Scores from assessments including:
   - Strength and Difficulties Questionnaire (SDQ)
   - Alabama Parenting Questionnaire

The models predict two target variables:
- **ADHD_Outcome**: Type of Diagnosis (0=Other/None, 1=ADHD)
- **Sex_F**: Sex of participant (0=Male, 1=Female)


## Repository Structure
```
- **ML_Powered_ADHD.ipynb**: Main analysis notebook containing all code, analysis, and results for the ADHD prediction project
```

## Key Features

- **Multi-outcome prediction** of both ADHD diagnosis and biological sex
- **Enhanced model comparison** with statistical significance testing
- **Sex-specific analysis** of brain connectivity patterns in ADHD
- **Interactive visualizations** of brain connectivity networks
- **SHAP-based interpretation** of model predictions
- **Feature importance analysis** highlighting sex differences
