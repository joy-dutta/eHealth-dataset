# eHealth

## Preparation of Synthetic IoMT Data for Cardiac Arrest
Data is the new fuel for every discipline in the modern world. To the best of the author's knowledge, in eHealth, the availability of IoMT data that helps researchers train their AI models for the prediction of cardiac arrest is not readily available. . A easily available and freely accessible dataset is the most important need for investigating any given area. To compensate for this, the present study conducts extensive research in this area to provide a synthesis dataset that eHealth researchers may use to test their AI/ML model. We have selected a particular medical condition, "cardiac arrest," for which we are producing synthesized IoMT data. This document will include all valid ranges of medical sensors (IoMT) for a subject in various scenarios (patient). The offered range is based on studies published in peer-reviewed publications and papers that have been vetted by well-established practitioners in this medical sector and may be used to build any amount of the synthetic dataset for cardiac arrest depending on the needs of the researcher. 

### Keywords: IoMT, Heart Attack, eHealth, Synthetic Dataset, AI/ML

### Python Notebook link to create synthetic dataset for: 
#### (a) Subject 1: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/Synthetic_DataSet_Preparation_IoMT_70yrs.ipynb) (Ptyhon Script for 70 Years Old Subject) 
#### (a) Subject 2: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/Synthetic_DataSet_Preparation_IoMT_40yrs.ipynb) (Ptyhon Script for 40 Years Old Subject)



### Download Dataset
#### Dataset 1: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/synthetic_IoMT_70.csv) (IoMT Dataset for 70 Years Old Subject 1)

#### Dataset 2: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/synthetic_IoMT_40.csv) (IoMT Dataset for 40 Years Old Subject 2)

## Dataset Description:

For this dataset, we used the pulse rate, breathing rate, distance traveled, speed, and oxygen level in the blood as five input features to predict a single target class feature, i.e., the binary prediction for cardiac arrest. Because of the unavailability of the IoMT data, we have created this synthetic IoMT dataset of two individuals with 120000 instances with six features in each dataset. 

### Notebook link for exploratory analysis of the dataset for Subject 1
IoMT Dataset exploration for Subject 1: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/IoMT_data_exploration_Subject1.ipynb)

### Notebook link for data validation with supervised machine learning-based models (Subject 1):
1. Logistic Regression: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/logistic_regression.ipynb)
2. Linear-SVM: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/support_vector_machine.ipynb)
3. Kernel-SVM: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/kernel_svm.ipynb)
4. Naive Bayes: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/naive_bayes.ipynb)
5. k-nearest neighbors (KNN): [Click Here](https://github.com/joy-dutta/eHealth/blob/main/k_nearest_neighbors.ipynb)
6. Decision Tree: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/decision_tree_classification.ipynb)
7. Random Forest: [Click Here](https://github.com/joy-dutta/eHealth/blob/main/random_forest_classification.ipynb)


## Cite this dataset
If you are using this dataset for your own experiment or research, you need to refer to the below work by the author:

### J.Dutta and D. Puthal, "IoMT Synthetic Cardiac Arrest Dataset for eHealth with AI-based Validation," 2023 IEEE Computer Society Annual Symposium on VLSI (ISVLSI), Iguazu Falls, Brazil, 2023 [Accepted]
