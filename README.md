# Open University Learning Analytics dataset analysis for student classification
## Abstract
This report outlines a project focused on analyzing the [Open University Learning Analytics dataset](https://analyse.kmi.open.ac.uk/open_dataset) using various statistical learning methods, with an emphasis on **classification models** and **feature selection**. The dataset encompasses information about seven courses held in the Virtual Learning Environment (VLE) of the Open University, including anonymized data about students and their interactions with course materials. The goal is to understand which variables influence student performance to improve the online learning experience.

Different classification models are compared, including logistic classifiers, linear discriminant analysis, quadratic discriminant analysis, naive Bayes, and K-Nearest Neighbors. 

The results indicate that logistic regression models outperform others, attributed to the dataset not satisfying assumptions made by alternative models, especially concerning the normality of predictors and the prevalence of categorical features. Logistic classifiers and the naive Bayes model, which incorporate categorical data, exhibit the highest accuracy. Notably, K-Nearest Neighbors, relying solely on numerical variables, performs the least effectively.
Recommendations for educational institutions are proposed based on these findings, such as offering special assistance to students with lower deprivation levels and education, understanding dynamics of successful modules, and monitoring students' interactions for timely interventions.

