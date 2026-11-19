Machine Learning for Steel Alloy Property Prediction
Problem: Predict the mechanical properties of steel alloys from chemical composition and investigate how to optimise compositions for desirable performance.
Methods, software and investigations:
•	Python programming: NumPy, Pandas, Scikit-learn, SciPy, Matplotlib and Seaborn.
•	Dataset processing: Worked with 312 alloy records and 14 elemental composition variables.
•	Machine learning: Multivariable linear regression using sklearn.linear_model.LinearRegression(fit_intercept=False).
•	Mathematical modelling: Represented composition-property relationships as \(\mathbf{y}=\mathbf{Ax}\), using a 3 × 14 coefficient matrix.
•	Property prediction: Tensile yield strength, ultimate tensile strength and elongation at fracture.
•	Cross-validation: Random shuffling, iron-content-based stratification, training/test separation and repeated model evaluation.
•	Feature analysis: Investigated elemental concentration against prediction error, including non-linear effects of carbon and alloying elements.
•	Classification: Categorised elongation into fragile, medium and strong classes.
•	Optimisation: Implemented constrained numerical optimisation using scipy.optimize.minimize, with elemental composition bounds, a total composition constraint of 100%, weighted mechanical-property objectives and a cost-related penalty for Ni and Co.
Reported model performance:
Model worked exactly how it should, achieving a 95% (first class grade)
Key learning: End-to-end machine-learning workflows, data preprocessing, regression, model validation, scientific Python programming, numerical optimisation and limitations of composition-only property prediction.
