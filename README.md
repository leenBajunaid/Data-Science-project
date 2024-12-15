# Predicting Pollster Rating Accuracy Using Pollster Data

### Authors: Sadeem Bin Mahfouz, Reem Bazarah, Leen Bajunaid

## Overview

This project explores the accuracy of pollster predictions in political races and identifies key factors influencing their reliability. Using historical polling data and advanced machine learning techniques, the goal is to predict pollster accuracy (`Simple Average Error`) and uncover the metrics that best forecast polling success.

### Research Question
**Can we predict the accuracy of a pollster’s predictions using historical performance metrics?**  
This project seeks to determine how features like `Predictive Plus-Minus` and `Races Called Correctly` influence the `Simple Average Error`, helping to identify reliable pollsters and improve polling methodologies.

---

## Repository Contents

- **`Data Sciences Proposal (2).ipynb`**: Contains the project proposal, including problem statement, research question, and initial data exploration.
- **`Data Sciences Report (2).ipynb`**: Includes the full report, detailing the research methodology, modeling, and results.
- **`Data Sciences Project.ipynb`**: The main project notebook with data preprocessing, model development, and result visualization.

---

## Codebook: Relevant Variables

| **Variable Name**         | **Description**                                                                                 | **Type**      |
|----------------------------|-------------------------------------------------------------------------------------------------|---------------|
| `Simple_Average_Error`     | The outcome variable indicating pollster prediction accuracy (lower values mean better accuracy). | Continuous    |
| `Predictive_Plus_Minus`    | Accuracy metric comparing predictions to actual outcomes.                                        | Continuous    |
| `Races_Called_Correctly`   | Number of races accurately predicted by the pollster.                                           | Continuous    |
| `Polls_Analyzed`           | Total number of polls analyzed for a given pollster.                                            | Continuous    |
| `House_Effect`             | Political bias indicator for the pollster.                                                     | Categorical   |
| `Mean_Reverted_Bias`       | Adjusted bias score after applying mean reversion techniques.                                   | Continuous    |
| `Misses_Outside_MOE`       | Frequency of predictions outside the margin of error.                                           | Continuous    |
| `Simple_Expected_Error`    | Expected error based on historical pollster performance.                                        | Continuous    |
| `Advanced_Plus_Minus`      | An advanced metric for prediction accuracy.                                                    | Continuous    |
| `Bias`                     | Systematic bias in pollster predictions.                                                       | Continuous    |
| `ADPA`                     | Average Distance from Polling Average, measuring deviations from the overall polling average.   | Continuous    |

---

## Success Metrics

- **R² (Coefficient of Determination)**: High values indicate a strong model fit.
- **Mean Squared Error (MSE)**: Low values signify closer alignment between predicted and actual `Simple Average Error`.
- **Feature Importance Analysis**: Identifies the most influential metrics for prediction accuracy.
---
 - "This README provides an overview of the project, details on the repository contents, a codebook for variables, and the success metrics used in the analysis. Feel free to contribute or raise any issues!"


