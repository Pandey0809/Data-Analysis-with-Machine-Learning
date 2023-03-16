# Diabetes Prediction
Analyzing various attributes on which diabetes directly depends and predicting if a person with a given health conditions has diabetes.

## Motivation
Project was created to make a comparison between the accuracy of predictions obtained from Support Vector Machine and Naivebayes algorithm. The goal of the project is to tune the two algorithms in such a way that the accuracy of prediction is maximized.

## Data-set
Data-set being used in this project can be found on kaggle or you can use this [link](https://www.kaggle.com/uciml/pima-indians-diabetes-database) to go directly to the data-set.

## Screen shots
-HeatMap

![alt text](https://github.com/Pandey0809/Data-Analysis-with-Machine-Learning/blob/myB/DiabetesDatabase-NaiveBayes-SVM-master/Images/Heatmap.png)

-Output using NaiveBayes<br />  

| index  | precision  | recall  | f1-score  | support  |  
| ---  | ---  | ---  | ---  | ---  |  
| `0`  | 0.82  | 0.85  | 0.83  | 150  |  
| `1`  | 0.70  | 0.64  | 0.67  | 81  |  
  | **micro avg** |      0.78  |    0.78  |    0.78 |      231 |
  | **macro avg**  |     0.76  |    0.75  |    0.75  |     231 |
| **weighted avg** |      0.78 |     0.78  |    0.78 |      231 |

-Output using SVM

| **index** | **precision** |   **recall** | **f1-score** |  **support** |
| --- | --- | --- | --- | ---|
| `0` |      0.82  |    0.87 |     0.85 |      103 |
| `1`   |    0.70    |  0.61 |     0.65     |   51 |
| **micro avg**    |   0.79   |   0.79  |    0.79    |   154 |
| **macro avg**     |  0.76   |   0.74  |    0.75   |    154 |
| **weighted avg** |      0.78   |   0.79  |    0.78  |     154 |
