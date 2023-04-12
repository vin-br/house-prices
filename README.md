# House Prices

Project Ownership : Vincent Boettcher

## Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Goal

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

## Metric

Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

## Minimum requirements

- Python 3.11.3
- Jupyter Notebook 6.5.4
- Numpy 1.24.2
- Pandas 2.0.0
- Matplotlib 3.7.1
- Seaborn 0.12.2
- Scikit-learn 1.2.2

## Quick install
```python -m venv venv```

```source /bin/activate/venv``` (for Windows)

```source venv/bin/activate``` (for macOS)

```pip install -r requirements.txt```

