# Titanic Preprocessing (EDA + Cleaning)

## Files
- data_preprocessing_intro_refined.ipynb
- figs/age_hist.png, figs/sex_count.png, figs/corr_numeric.png

## Data (Not included)
Kaggle から train.csv を取得し、titanic/ に置いて実行してください。

## Why (Policy)
- Age: 中央値で補完（外れ値耐性）
- Embarked: 最頻値で補完（欠損2件）
- Cabin: 有無フラグ化（欠損多数）
- Sex: 2値化、Embarked: one-hot
