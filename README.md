# DSCI 552 Homework 2

Regression analysis and KNN regression on the UCI Combined Cycle Power Plant data set, plus ISLR exercises 2.4.1 and 2.4.7.

## Structure

```
.
├── data/
│   └── CCPP/
│       ├── Folds5x2_pp.xlsx
│       └── Readme.txt
├── notebook/
│   └── Agudanmu_Fnu_HW2.ipynb
└── requirements.txt
```

## How to run

```bash
pip install -r requirements.txt
cd notebook
jupyter notebook Agudanmu_Fnu_HW2.ipynb
```

The notebook reads the data with the relative path `../data/combined_cycle_power_plant/Folds5x2_pp.xlsx`, so it should be run from the `notebook/` folder. Only Sheet 1 of the workbook is used.
