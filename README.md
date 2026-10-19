# Tokyo 2020 Olympics – Statistical Analysis & Regression

## Project Overview

During Semester 3 of my ICT & Business studies at Fontys University of Applied Sciences, I completed a data analytics project investigating the relationship between athlete participation and medal success at the Tokyo 2020 Olympics.

Using **Python, Pandas, exploratory data analysis (EDA), and linear regression**, I investigated whether the number of athletes and disciplines a country participates in is associated with its total medal count.

## Research Questions

1. Is there a linear relationship between the number of athletes a country sends and the total number of medals it wins?
2. Is there a linear relationship between the number of disciplines a country participates in and its total medal count?

## Data Analysis & Methodology

The project followed four main stages:

1. **Data Preparation:** Cleaned and combined athlete participation and medal datasets into a dataset containing 93 medal-winning countries.
2. **Exploratory Data Analysis:** Investigated distributions, correlations, outliers, and relationships using statistical summaries and visualisations.
3. **Linear Regression:** Developed two Ordinary Least Squares (OLS) regression models to analyse athlete count and discipline count separately.
4. **Model Evaluation:** Evaluated R², statistical significance, residuals, and regression assumptions to assess the reliability of the results.

## Key Findings

| Metric | Athlete Count | Discipline Count |
|---|---|---|
| Correlation (r) | 0.875 | 0.741 |
| R² | 0.766 | 0.549 |
| p-value | < 0.001 | < 0.001 |

Both variables showed statistically significant positive relationships with medal totals.

**Athlete count was the stronger predictor**, explaining approximately 76.6% of the variation in medal totals, compared with 54.9% for discipline count.

However, the analysis also identified limitations involving outliers, regression assumptions, and factors not included in the models. The findings apply to the 93 medal-winning countries analysed and do not establish causation.

## Tools & Technologies

| Area | Tools & Methods |
|---|---|
| Programming & Data Analysis | Python, Pandas, NumPy, Jupyter Notebook |
| Data Visualisation | Matplotlib, Seaborn |
| Statistical Modelling | Statsmodels, SciPy, Linear Regression (OLS) |
| Model Evaluation | R², Correlation, p-values, Residual Analysis |

## My Contribution

I prepared and combined the Olympic datasets, performed exploratory data analysis, and developed two linear regression models to investigate the research questions.

I evaluated the models using statistical measures and assumption checks, interpreted the results, and presented the findings.

This project strengthened my understanding of **data preparation, statistical modelling, regression evaluation, and communicating analytical findings**.

## Repository Structure

| Deliverable | Description |
|---|---|
| [**Olympics Analysis – Jupyter Notebook**](https://github.com/patritsia-marinova/Tokyo-2020-Olympics-Statistical-Analysis/blob/main/Olympics%20Analysis%20%2B%20Presentation/olympics_final.ipynb) | Data preparation, exploratory data analysis, linear regression modelling, and statistical evaluation |
| [**Olympics Presentation**](https://github.com/patritsia-marinova/Tokyo-2020-Olympics-Statistical-Analysis/blob/main/Olympics%20Analysis%20%2B%20Presentation/olympics_presentation_v2.pptx) | Research questions, regression results, model comparison, and key findings |

Both deliverables are located in the **Olympics Analysis + Presentation** folder.

## Project Outcome

The analysis identified statistically significant positive relationships between Olympic participation and medal totals, with athlete count showing a stronger association than discipline count.

By preparing datasets, conducting exploratory analysis, developing regression models, and evaluating statistical assumptions, I gained practical experience in **Python, data analytics, statistical modelling, and interpreting data-driven findings**.

The project also strengthened my ability to critically evaluate statistical results and communicate conclusions, providing a foundation for future Data Analytics and Machine Learning projects.
