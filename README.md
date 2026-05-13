# EEG-Based Clinical Decision Support Tool — Product Feasibility & BA Study

## 1. Project Overview
This project evaluates the feasibility of an AI-assisted clinical decision support workflow for schizophrenia screening using EEG-derived healthcare data.

The study combines:
- Business Analysis (BA)
- Healthcare Analytics
- Machine Learning Validation
- Clinical Workflow Evaluation
- Responsible AI Considerations

The objective was not to build a deployable diagnostic system, but to assess whether machine learning could support early-stage psychiatric decision-support workflows in a clinically responsible manner.

---

## 2. Business Objective
To evaluate whether EEG-based machine learning models can support mental health clinicians through:
- Early-stage risk classification
- Decision-support assistance
- Structured analytical workflows
- AI-assisted healthcare screening feasibility

---

## 3. Technical Validation Summary
- Dataset: Publicly available EEG-derived NREM sleep features
- Subjects: 130
- Features: ~2,894 EEG-derived features
- Classification Type: Schizophrenia vs Control

### A. Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### B. Final Results

| Metric | Result |
|---|---|
| Best Model | SVM |
| Accuracy | ~84.6% |
| ROC-AUC | 0.896 |
| Cross-Validation AUC | 0.835 ± 0.105 |
| Validation Method | 5-Fold Stratified Cross-Validation |

---

## 4. Tools & Technologies
- Python
- Pandas
- NumPy
- scikit-learn
- Jupyter Notebook
- Matplotlib
- Lucidchart
- MS Word

---

## 5. End-to-End Workflow

1. Data Cleaning & Validation  
2. Missing Value Handling  
3. Feature Selection (ANOVA SelectKBest)  
4. Stratified Train-Test Split  
5. Pipeline-Based Preprocessing  
6. ML Model Training & Comparison  
7. Cross-Validation & Evaluation  
8. Clinical Feasibility Assessment  
9. BA Documentation & Workflow Modeling  

---

## 6. Business Analysis Components

This project was additionally evaluated from a healthcare product and consulting perspective through:
- Project Charter
- BRD (Business Requirements Document)
- As-Is vs To-Be Workflow Modeling
- Feasibility Assessment & Go/No-Go Evaluation
- AI Deployment Constraints Assessment
- Responsible AI Considerations Assessment

---

## 7. Key Insights
- Small healthcare datasets are highly prone to overfitting
- Feature selection is critical in high-dimensional biomedical data
- ROC-AUC and F1-score provide more reliable evaluation than accuracy alone
- AI-assisted healthcare systems require strong clinical validation before deployment
- Responsible AI and regulatory considerations are essential in healthcare analytics
- Technical feasibility alone is insufficient for healthcare AI deployment readiness

---

## 8. Limitations
- Limited sample size (130 subjects)
- No external validation dataset
- Pre-extracted EEG features used (not raw EEG signals)
- No prospective clinical validation study conducted
- Results are exploratory and not clinically deployable

---

## 9. Repository Structure

```text
business-analysis/        → BA documentation & workflow artifacts
technical-validation/     → ML notebook & technical validation
visuals/                  → ROC curves, confusion matrix, workflow visuals
data/                     → Dataset
```

---

## 10. Business Analysis Documentation

1. [Project Charter](business-analysis/01_Project_Charter_EEG_CDS.pdf)

2. [Business Requirements Document (BRD)](business-analysis/02_BRD_EEG_CDS.pdf)

3. [As-Is vs To-Be Workflow](business-analysis/03_AsIs_ToBe_Workflow.pdf)

4. [Feasibility Assessment & Go/No-Go Evaluation](business-analysis/04_Feasibility_Assessment_EEG_CDS.pdf)

5. [AI Deployment Constraints](business-analysis/05_AI_Deployment_Constraints_EEG_CDS.pdf)

6. [Responsible AI Considerations](business-analysis/06_Responsible_AI_Considerations_EEG_CDS.pdf)

---

## 11. Project Positioning

This project demonstrates:
- Healthcare analytics capability
- Machine learning validation workflow design
- Business analysis and workflow modeling
- Clinical decision-support feasibility evaluation
- Responsible AI and healthcare governance awareness
- Structured problem-solving in healthcare AI contexts

---

## 12. Author

Bhumi Nagar  
MBA, Business Analytics (STEM) — Saint Peter’s University  
Bachelor of Pharmacy — L.M. College of Pharmacy