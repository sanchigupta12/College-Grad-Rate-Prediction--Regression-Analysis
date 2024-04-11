# Regularization Techniques in Machine Learning

## Author
Sanchi Gupta

## Date
2024-02-04

## Introduction
This project focuses on regularization techniques, specifically Ridge and Lasso regression, and compares them with Stepwise regression. Using the ISLR library’s College dataset, the project aims to predict the graduation rate while exploring the impact of different lambda values on model performance.

## File Structure
- `regularization.rmd`: R Markdown document containing the full analysis, including code, results, and discussion.
- `regularization.html`: Compiled HTML report generated from the R Markdown file, presenting the analysis in a readable format.
- `README.md`: This file.

## Dependencies
- R language
- R libraries: `ISLR`, `glmnet`, `Matrix`, `ggplot2`, `caret`, `knitr`, `kableExtra`

## How to Run
1. Ensure R and all required libraries are installed.
2. Clone the repository to your local machine.
3. Open the `regularization_analysis.R` script in RStudio or your preferred R environment.
4. Run the script to perform the analysis and generate the output.

## Overview of Analysis
- Data is split into training and test sets.
- Ridge and Lasso regression models are fitted using `cv.glmnet` to find optimal lambda values.
- Model performance is evaluated using RMSE (Root Mean Square Error) on both training and test sets.
- A comparison is made with a Stepwise regression model to identify the best predictive model.

## Conclusion
The report details the methodology, results, and interpretation of different regularization techniques. While each method has its advantages, Lasso regression with lambda.min showed the best predictive accuracy in this study, though Stepwise selection slightly outperformed both regularization methods in terms of RMSE on the test set.

## References
- Various sources including OpenAI, Northeastern University materials, and Quora for conceptual understanding and technical guidance.
