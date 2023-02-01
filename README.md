<h1 align="center">Run-Walk Prediction </h1>
<p align="center">
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

<p  align="justify">
Human activity recognition (HAR) aims to classify a person's actions from a series of measurements captured by sensors.
Nowadays, collecting this type of data is not an arduous task. With the growth of the Internet of Things, almost everyone has some gadget that monitors their movements. It can be a smartwatch, a pulsometer, or even a smartphone.
Usually, this is performed by following a fixed-length sliding window approach for the features extraction. Here two parameters need to be fixed: the size of the window and the shift. 
</p>
<br> 
These are some of the data you could use: <br>
      ●	Body acceleration.  <br>
      ●	Gravity acceleration.  <br>
      ●	Body angular speed.  <br>
      ●	Body angular acceleration. <br>
      ●	Etc. 


The objective of this project is to analyze a dataset of human activities containing running and walking. Later imported some python libraries and implemented a few nonlinear ML models on a dataset. After acquiring the accuracies from respective models, the model with maximum accuracy was selected for this dataset.


**Machine Learning Models Used**

```
KNN
CNN
SVM
Naive Bayes
```

**Result Images**

 1.Accuracy by Logistic Regression
 ![Read Image](/Images/CNN.png)
 2.Accuracy by KNN
 3.Accuracy by SVM
 4.Accuracy by Naive Bayes
 5.Accuracy by CNN model
 6.Confusion Matrix
 7.Overall Accuracy of All models we get that KNN has highest whereas Logistic Regression has Lowest
