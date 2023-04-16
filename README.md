# Diabetes Patient Death Prediction using Machine Learning on MIMIC-IV Dataset
This repository contains code and data for predicting the likelihood of death in diabetes patients using machine learning techniques applied to the MIMIC-III dataset. MIMIC-III (Medical Information Mart for Intensive Care III) is a large, freely available dataset of de-identified electronic health records of patients admitted to the critical care units of a large tertiary care hospital in the United States.

## Dataset
The MIMIC-IV dataset is provided by the MIT Laboratory for Computational Physiology, and is freely available to researchers who agree to the terms of use. You can find information on how to obtain the dataset here. The dataset used in this project includes data on diabetes patients who were admitted to the hospital's intensive care unit between 2001 and 2012.

## Methodology
The project involves preprocessing the MIMIC-III dataset, performing feature engineering to extract relevant features, training machine learning models using different algorithms, and evaluating the performance of the models using various metrics. The models considered include logistic regression, random forest, and gradient boosting.

## Code
The code for the project is provided in the code directory. The code is written in Python and uses various libraries such as Pandas, NumPy, and Scikit-learn. The code is organized into different scripts for each step of the process, including data preprocessing, feature engineering, model training, and evaluation.

## Results
The results of the project are presented in the results directory. This includes figures and tables that show the performance of the different models on the test dataset, as well as a report summarizing the findings of the project.
 
## Conclusion
This project demonstrates the feasibility of using machine learning techniques to predict the likelihood of death in diabetes patients using the MIMIC-III dataset. The results show that the gradient boosting algorithm performs the best among the models considered, achieving an AUC of 0.85 on the test dataset.

## References
Johnson AE, Pollard TJ, Shen L, Lehman LH, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. MIMIC-III, a freely accessible critical care database. Scientific Data, 3:160035, 2016.

Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, and Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals. Circulation, 101(23):e215-e220, 2000.

Pedregosa F, Varoquaux G, Gramfort A, Michel V, Thirion B, Grisel O, Blondel M, Prettenhofer P, Weiss R, Dubourg V, Vanderplas J, Passos A, Cournapeau D, Brucher M, Perrot M, and Duchesnay E. Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12:2825-2830, 2011.
