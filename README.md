# TMLC-NLP-Submission
This repository contains the solution to the NLP Text Claasification problem posted by TMLC for its fellowship program for the year 2022.

The dataset provided is a text classification on e-commerce websites based on four categories: Household(0), Electronics (1), Books (2), Clothing & Accessories(3).

The file format is .csv and it consists of 50424 rows and 2 columns:
1. Column 1- Broad classification of the products into the above mentioned categories
2. Column 2- Product Description

The following graph demonstrates the frequency of occurence of each classification in our data:


![image](https://user-images.githubusercontent.com/108565358/192588817-8b7c60e9-8353-485b-bce7-98fccedc3ae0.png)

On performing text classification and using the Multinomial Naive Bayes algorithm, we obtain the following heatmap:

![image](https://user-images.githubusercontent.com/108565358/192589194-670a0b43-c756-4367-9013-0dadaa4fe5c0.png)



Below is a classification report displaying various parameters such as the f1 score, precision and recall:

Naive Bayes Accuracy: 0.9427551560021152
Naive Bayes Precision: 0.9553162213090072
Naive Bayes Recall: 0.9355371850677946

                        precision    recall  f1-score   support

           Electronics     0.9719    0.9144    0.9423      3552
             Household     0.9842    0.9422    0.9628      2580
                 Books     0.9635    0.9048    0.9332      3152
Clothing & Accessories     0.9017    0.9807    0.9395      5844

              accuracy                         0.9428     15128
             macro avg     0.9553    0.9355    0.9444     15128
          weighted avg     0.9451    0.9428    0.9428     15128
