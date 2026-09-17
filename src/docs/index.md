**FSD310 - Fundamentals of Decision Making**
# Statistical Foundations of Machine Learning

This 15h course develops important aspects of statistical modelling, which are particularly related to machine learning.

Schedule | | |
| --- | --- | --- |
07/09 AM | Descriptive Statistics[^1] | 3h |
08/09 AM | Inferential Statistics[^1] | 3h |
09/09 AM | Linear models[^1] | 3h |
09/09 PM | Simple Linear regression and maximum likelihood | 3h |
15/09 PM | Multiple Linear regression | 4h |
23/09 PM | Mixed-effects models | 3h |
28/09 PM | **Written Exam**  | 1h |
30/09 PM | Introduction to Extreme Value Statistics | 2h |
07/10 PM | Application to Imbalanced Classification | 2h |

[^1]: Shared with SD

Course 1 and 2 reviews the mathematical notions that will underlie machine learning. In particular, the notions of random variables, probability density and empirical estimation of model parameters will be rigorously defined and illustrated.

Course 3 is central in this course as it presents the linear regression model from a statistical point of view, but opens up questions that are essential in machine learning, such as overfitting and cross-validation.

These issues are developed in chapter 3, which deals with regularization and cross-validation but also develops the concepts of bias-variance trade-off and curse of dimensionality.

Chapters 4 and 5 push the statistical modeling aspects introduced in chapter 3 to make clear how the randomness modeled in different random variables allows to build a statistical test (chapter 4 on ANOVA) or to estimate the parameters of a relatively complex model from observed data (chapter 5 on mixed models).

Finally, chapter 6 makes two openings on two classic linear models, both in machine learning and in statistics, which are the logistic regression and the PLS method.

## Resources 

### Descriptive statistics

[Slides](cours/statistique.pdf)

### Inferential Statistics

[Slides](cours/stats_inf_proba.pdf)

### Linear models

Slides

- [Topo historique](cours/1_TopoHistorique.pdf)

- [Statistique et Machine Learning pour la science des données](cours/2_StatML1.pdf)

Notebooks


- [Likelihood](notebooks/2a_likelihood.ipynb)

- [Linear regression](notebooks/2b_linear_regression.ipynb)


### Simple Linear regression and maximum likelihood

Slides

- [Linear Regression](cours/3_Regression_Lineaire.pdf)

Notebooks


- [Exercise 1: Simple regression](notebooks/Exo1_SimpleRegression.ipynb)

- [Exercise 2: Maximum Likelihood](notebooks/Exo2_MaxLikelihood.ipynb)

- [Exercise 3: Maximum Likelihood](notebooks/Exo3_MaxLikelihood2.ipynb)

- [Exercise 4: Linear regression errors](notebooks/Exo4_LinearRegressionErrors.ipynb)

- [Exercise 5: Linear regression optimization](notebooks/Exo5_LinearRegressionOptim.ipynb)

- [Exercise 6: Multiple linear regression](notebooks/Exo6_RegressionMultiple.ipynb)

Data

- [QuantifiedDataExo1_3.csv](notebooks/QuantifiedDataExo1_3.csv)

### Model Selection and Cross-Validation

Slides

- [Multivariate Linear Regression](cours/4_Selection_de_modele.pdf)


Notebooks

- [Exercise 7: Multiple regression and regularization](notebooks/Exo7_RegressionMultipleReg.ipynb)

- [Exercise 8: Real Data Analysis](notebooks/Exo8_RealDataAnalysis.ipynb)

Data

- [RealMedicalData.csv](notebooks/RealMedicalData.csv)

