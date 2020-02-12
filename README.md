# Survival-Analysis

A prognostic model should not enter clinical practice unless it has been demonstrated that it performs a useful role. External validation denotes evaluation of model performance in a sample independent of that used to develop the model. Unlike for logistic regression models, external validation of Cox models is sparsely treated in the literature. Successful validation of a model means achieving satisfactory discrimination and calibration (prediction accuracy) in the validation sample. Validating Cox models is not straightforward because event probabilities are estimated relative to an unspecified baseline function.

In this analysis, we have developed a model using TCGA data (attached in a document). 
We divided dataset into trainig and validation sets and created two models - kitchen sink model and smaller model with backwards stepwise selection.
Further, we created a prognostic index (PI) using a smaller model and validated th PI on validation set. For validating PI, we used three different approches:
1. Method-1: coefficient on PI on validation set
2. Method-2: Checking model misclassification/fit
3. Method-3: Measures of discrimination
4. Method-4: Kaplan-Meier Analysis
5. Method-5: Logrank/ Cox P-Values
6. Method-6: Hazard Ratio

The attached paper used for refrerence. 
