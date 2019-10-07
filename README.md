# 2015-NIEHS-MIxtures-Workshop
Simulated data and related materials from the 2015 NIEHS Mixtures Workshop

Data Set #1:
Chemical Mixture Simulated Data
These synthetic data can be considered as the results of a prospective cohort epidemiologic study. The outcome cannot cause the exposures (as might occur in a cross-sectional study). Correlations between exposure variables can be thought of as caused by common sources or modes of exposure. The nuisance variable Z can be assumed to be a potential confounder and not a collider.
Structure of data file:
Name: DataSet1.xls (121KB)
Format: Excel file; the first row is a header each row represents a subject
Number of records: 500
Data per subject: Y, X1, X2, X3, X4, X5, X6, X7, Z
Y = outcome data, 1 continuous variable
X1 - X7= exposure data, 7 continuous variables
Z: potential confounder, binary
Additional information:
For purposes of Data Set #1, there is no loss to follow up, missing or censored data, mismeasurement of the variables (Y, Xi, Z), or many of the other potential biases. One may also assume that the seven exposure variables X1, X7 and Z are not intermediate variables and not colliders. There are no other confounders or effect measure modifiers. Random noise has been added to the outcome variable.

Data Set #2:
Mixture Simulated Data with an Environmentally Relevant Complex Correlation Pattern
This data file is intended to represent data from a cross-sectional study of 14 biomarkers (e.g., PCBs, dioxins, furans) from biomonitoring data potentially associated with a biomarker of effect (e.g., ALT as a marker of liver toxicity). Three covariates are also included, one binary and two continuous.
Structure of data file:
Name: DataSet2.xls (198KB)
Format: tab delimited Excel file; the first row is a header each row represents a subject
Number of records: 500
Variables: Y, X1, X2, X3, X4, X5, X6, X7, X8, X9, X10, X11, X12, X13, X14, Z1, Z2, Z3
Y = The outcome, a continuous variable.
X1 - X14 = Fourteen exposure biomarkers. Each is a continuous variable.
Z1-Z2: Potential confounders that are continuous.
Z3: A potential confounder that is binary.
Additional information:
Data are complete (no missing data).
For both data sets, please answer as many of the following questions in your analysis:
Which exposures contribute to the outcome? Are there any that do not? (Qualitative)
Which exposures contribute to the outcome and by how much? (Quantitative)
Is there evidence of "interaction" or not? Be explicit with your definition of interaction (toxicologists, epidemiologists and biostatisticians tend to think about this quite differently).
What is the effect of joint exposure to the mixture? (Qualitative)
What is the joint dose-response function? For example, if you can describe Y as a function of the exposures, what is your estimate of the function Y=f(X1,…,Xp)? (Quantitative)
Provide metrics for your answer. For example, consider adjusted r square or root mean square error, etc.
Analysts may also provide a description of the joint distribution of the exposure data.
