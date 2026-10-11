# Spatial Modeling of Poverty in Papua, Indonesia

## About
This project examines spatial variation in poverty rates across regencies and cities in Papua, Indonesia. Multiple linear regression is used as an initial model, followed by Geographically Weighted Regression (GWR) to explore geographically varying relationships. K-Means clustering is also applied to group regions based on their poverty rates.

The project was developed for the **Statistical Project for Smart Students (SPSS) 2024**, organized by Himasta, BINUS University, where the team achieved **Top 4**.

## Project Analysis
- [Access Project Files on Google Drive](https://drive.google.com/drive/folders/1Un5e2GmhNR9AfTXdfUOGlHwPw2kOBqvX?usp=sharing)

## Dataset
- **Geographic coverage:** 42 regencies and cities across Papua, Indonesia, as defined in the project dataset.
- **Observation unit:** Regency/city.
- **Response variable:** `y` — percentage of the population living in poverty.
- **Predictor variables:** `x1`, `x2`, `x5`, `x6`, and `x7` in the final model.
- **Spatial data:** Regency/city boundary shapefile from the December 2019 Dukcapil administrative boundaries dataset.
- **Data files:** `dataGWRpapua.xlsx` and the administrative boundary shapefile.

The provided analysis does not document the exact reference year or full variable definitions for each predictor. The original input files are available through the project folder.

## Methods
- **Exploratory Data Analysis:** Examined poverty distribution, regional variation, and correlations among variables.
- **Multiple Linear Regression:** Established a baseline model and assessed multicollinearity using VIF.
- **Model Refinement:** Removed `x3` and `x4` from the initial model to reduce multicollinearity.
- **Geographically Weighted Regression:** Used a Gaussian kernel and selected the bandwidth using the AICc criterion.
- **Spatial Visualization:** Mapped poverty rates and local GWR coefficient estimates.
- **K-Means Clustering:** Evaluated cluster counts from 2 to 10 using average silhouette width, based on scaled poverty-rate values.

## Achievement
**Top 4 — Statistical Project for Smart Students (SPSS) 2024**  
Himasta, BINUS University

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
