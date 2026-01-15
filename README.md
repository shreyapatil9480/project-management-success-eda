[![Python CI](https://github.com/shreyapatil9480/project-management-success-eda/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/project-management-success-eda/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Project Management Success Eda

Which customers are likely to churn?

**Stakeholder:** Customer Success Lead

## Key Insights

- Tenure under 6 months doubles churn risk for basic-tier accounts.
- Support ticket volume above 5 is a leading churn indicator.
- Premium tier churn is driven more by ticket severity than volume.

## Dataset

Primary file: `data/customer_tenure.csv`  
Target variable: `churned`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/exploratory_analysis.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Tune class weights and add SHAP explainability.

---
*Analytics portfolio project — 2025-09*

<!-- build 6 -->

### Implemented

```bash
pip install -r requirements.txt
python src/train.py && python src/explain.py
```
