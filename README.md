# Predict_Flight_Delays

Machine Learning Model to predict the probability of delay for flights landing and taking off from SCL airport

The model is programmed in a *Jupyter notebook* named `solution.ipynb` located in the current folder.

## Dataset

The dataset is located in the `input` folder, and presents a binary classification problem with imbalanced classes (4.4 to 1).

## Model selected

3 models with algorithms compatible with imbalanced classification were evaluated and compared.

1. LogisticRegression Classifier
2. Support Vector Classification
3. Random Forest Classifier

Out the 3, the best model found was the `Random Forest Classifier` with a *weighted F-1 score* of 0.76 using 5-fold cross validation.

When using the full dataset, the *weighted F-1 score* increased to 0.77, and after hyper-parameter tuning it increased to 0.78

## How to run

To install the necessary packages, the virtual environment must be set up with:

> pipenv shell

> pipenv install

After that, you should open the notebook and point the kernel to the new activated virtual environment.

Cells can be re-run, but the latest output was saved to show the final results and plots.