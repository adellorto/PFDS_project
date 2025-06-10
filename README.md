# GNI and Renewable Energy Analysis

This repository contains a Jupyter Notebook exploring the relationship between Gross National Income (GNI) per capita and renewable energy consumption across countries. The analysis uses public datasets to investigate trends from 1990 through 2022 and attempts to visualize possible correlations.

## Contents

- `EPA11A_project_group_22.ipynb` – the main notebook with the data cleaning, exploration, visualizations and conclusions.
- `gross-national-income-per-capita-undp.csv` – GNI per capita dataset from the United Nations Development Programme.
- `renewable-energy-consumption.csv` – Renewable energy consumption dataset from the World Bank.

## Analysis Methods

The notebook begins by cleaning both datasets. Missing yearly data is filled using linear interpolation with forward and backward fills for edge years. Descriptive statistics are calculated, and several plots are generated, including line charts of time trends, scatter plots comparing countries, and bar charts for extreme values. Finally, a linear regression model is used to explore whether GNI can predict renewable energy consumption.

## Usage

Open the notebook in Jupyter and execute the cells in order. The datasets are already included in the repository. The notebook relies only on common Python libraries such as `pandas`, `matplotlib` and `seaborn`.

## Authors

The project was prepared by Alessandro Dell'Orto together with two other collaborators. It was produced as a university project for the MSc in Engineering and Policy Analysis at TU Delft for the course "Programming for Data Science".
