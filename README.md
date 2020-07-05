# Loan_Regressions

Using different regression tools, I tried to create a algorithm that would find risky loans.  Out of all the oversampling, undersampling and decision tree options, the AdaBoost Classifier is the best option to find loans that are going to be high or low risk.  It had the best presicion, sensitivity, f1 and accuracy score.

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.06      0.93      0.92      0.11      0.92      0.85       101
   low_risk       1.00      0.92      0.93      0.96      0.92      0.85     17104

avg / total       0.99      0.92      0.93      0.95      0.92      0.85     17205

