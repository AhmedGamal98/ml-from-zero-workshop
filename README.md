# Machine Learning from Zero: Workshop Material

> Material from a machine-learning workshop I presented at my college: multiple linear regression built from scratch with gradient descent, then compared with scikit-learn.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## What the notebook covers

1. **Load and explore** the AdventureWorks customer data (demographics and average monthly spend).
2. **Prepare features:** encode categorical columns and scale numeric values.
3. **Build the model without a library:** the cost function, gradient descent and the prediction step written in NumPy.
4. **Build the model with scikit-learn:** the same task with `LinearRegression`.
5. **Compare:** RMSE and R² of both approaches (R² about 0.94).

## Files

| File | Description |
| --- | --- |
| `Multiple Regression/multiple-regression.ipynb` | Workshop notebook |
| `Multiple Regression/AdvWorksCusts.csv` | Customer features |
| `Multiple Regression/AW_AveMonthSpend.csv` | Target: average monthly spend |

## Run it

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook "Multiple Regression/multiple-regression.ipynb"
```

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
