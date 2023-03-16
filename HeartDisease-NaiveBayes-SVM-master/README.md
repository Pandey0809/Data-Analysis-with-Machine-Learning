# HeartDisease Prediction
Analyzing various attributes on which Heart Disease directly depends and predicting if a person with a given health conditions has heart disease.

## Motivation
Project was created to make a comparison between the accuracy of predictions obtained from Support Vector Machine and Naivebayes algorithm. The goal of the project is to tune the two algorithms in such a way that the accuracy of prediction is maximized.

## Data-set
Data-set being used in this project can be found on kaggle or you can use this [link](https://www.kaggle.com/ronitf/heart-disease-uci) to go directly to the data-set.

## Screen shots
-HeatMap

![alt text](https://github.com/Pandey0809/Data-Analysis-with-Machine-Learning/blob/myB/HeartDisease-NaiveBayes-SVM-master/Images/Heatmap.png)

-Output using NaiveBayes<br />  

| **index**  | **precision**  | **recall**  | **f1-score**  | **support**  |  
| ---  | ---  | ---  | ---  | ---  |  
| `0` |      0.71 |     0.57 |     0.64   |     61 |  
|  `1`    |   0.78    |  0.87  |    0.82    |   108 |  
|  **micro avg**    |   0.76   |   0.76    |  0.76    |   169 |  
|  **macro avg**  |     0.75   |   0.72  |    0.73  |     169 |  
| **weighted avg**     |  0.76  |    0.76 |     0.76    |   169 |  

-Output using SVM

| **index** | **precision** |   **recall** | **f1-score** |  **support** |
| --- | --- | --- | --- | --- |
| `0` |      0.73 |     0.61 |     0.66 |       61 |  
| `1`     |  0.80   |   0.87  |    0.83    |   108 |  
| **micro avg**   |    0.78  |    0.78   |   0.78  |     169 |  
| **macro avg**     |  0.76    |  0.74     | 0.75   |    169 |  
| **weighted avg**     |  0.77  |    0.78    |  0.77    |   169 |  
