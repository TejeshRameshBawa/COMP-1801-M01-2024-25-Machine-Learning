# Metal Parts Durability

Lifespan prediction and usability classification using regression and neural-network models. MSc machine learning coursework, University of Greenwich.

![Neural-network classification confusion matrix from the coursework](preview.png)

## Problem

Can production attributes, chemical composition and defect counts help predict a metal part's lifespan and classify usability against a lifespan threshold of 1,500?

## Approach

- Explored distributions, correlations and outliers in the supplied manufacturing dataset.
- Prepared features and compared linear regression with an artificial neural network for lifespan prediction.
- Compared logistic regression with a neural network for usability classification.
- Used train/test evaluation, hyperparameter search, regression metrics and confusion matrices to examine performance and errors.

## Reported results

The coursework reports approximately **R² = 0.92** for the neural-network lifespan model and **93% classification accuracy** for the neural-network usability model. R² describes explained variation; it is not a regression 'accuracy' percentage.

These results describe the academic evaluation in the report, not a deployed quality-control system. Model errors and the cost of misclassification remain important considerations for any practical use.

## Explore the work

- [Portfolio report](portfolio-report.pdf).
- [Original notebook](COMP1801MachineLearningCoursework.ipynb).
- [Dataset](COMP1801_Coursework_Dataset.csv).
- [Notebook export as PDF](COMP1801MachineLearningCoursework%20Code.pdf).

## Run or inspect

1. Open the notebook in Jupyter or Google Colab.
2. Install `pandas numpy matplotlib seaborn scikit-learn` and a notebook environment.
3. In Colab, upload `COMP1801_Coursework_Dataset.csv` to `/content/`. For a local run, replace both `/content/COMP1801_Coursework_Dataset.csv` loading paths with the local filename.
4. Run cells in order and inspect the held-out metrics and confusion matrices.

The original notebook and saved outputs are preserved. A fresh end-to-end run and compatibility with current library versions have not been verified.

## Context

Academic project by Tejesh Ramesh Bawa. The preview comes from the report, and the portfolio copy omits the student identifier.
