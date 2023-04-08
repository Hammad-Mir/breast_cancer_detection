# breast_cancer_detection

In this project, I built a classifier for identifying benign or malignant breast tissue samples based on cytological characteristics. The dataset used contains 699 tissue samples, each classified into benign or malignant classes, and nine cytological characteristics on a 1 to 10 scale. The project begins with exploratory data analysis, including data cleaning and numerical and graphical summaries. Various classification methodologies, such as logistic regression, regularization with logistic regression, and discriminant analysis, were implemented to identify the best classification model based on their performance on predictive accuracy or error rate.

Skills demonstrated: Data pre-processing, exploratory data analysis, classification methodologies (logistic regression, regularization with logistic regression, discriminant analysis), data visualization, statistical analysis.

Tools and technologies used: R programming language, RStudio IDE, mlbench package, ggplot2 package, caret package, glmnet package, MASS package.

Outcome: Linear Discriminant Analysis was found to be the best classification model for this dataset, with a slight drop in accuracy for the 6 predictor model. However, when using priors that better reflect the real-world prevalence of breast cancer, Quadratic Discriminant Analysis performed the best in terms of classification accuracy.
