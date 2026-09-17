# Forecasting and Regression Analysis

Coursework for **IN6049**, School of Engineering and Sciences, Tecnológico de Monterrey,
September – December 2026. One folder per session: `week-1`, `week-2`, …

## Contents

| Folder | Topic | Data |
|---|---|---|
| `week-1` | Simple linear regression and inference | Salary vs. years of experience, *n* = 30 |

## week-1

`L1_simple_linear_regression_salary.ipynb` follows Kutner et al. (2005), Ch. 1–2: least
squares estimation, inference on $\beta_1$, confidence vs. prediction intervals, ANOVA and
the *F* test, $R^2$, and residual diagnostics. Each quantity is computed from its formula
and cross-checked against `statsmodels` OLS.

$$\hat{Y} = 25{,}792.20 + 9{,}449.96\,X$$

| $s\{b_1\}$ | 95 % CI for $\beta_1$ | $t^*$ | $F^*$ | $R^2$ |
|---|---|---|---|---|
| 378.75 | [8 674, 10 226] | 24.95 | 622.51 | 0.957 |

`week-1-presentation.pdf` — session presentation.

## Running it

```bash
cd week-1
python3 -m venv .venv
.venv/bin/pip install numpy pandas scipy statsmodels matplotlib jupyter
.venv/bin/jupyter lab
```

Tested on Python 3.12.5 · numpy 2.5.3 · pandas 3.0.5 · scipy 1.18.1 · statsmodels 0.15.0 ·
matplotlib 3.11.2.

## Reference

M. H. Kutner, C. J. Nachtsheim, J. Neter and W. Li, *Applied Linear Statistical Models*,
5th ed. New York: McGraw-Hill/Irwin, 2005.

## Team

*[names]*
