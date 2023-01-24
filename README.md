# Module 18 challenge
The purpose of this challenge was to evaluate several machine learning models to see how effective they are at analyzing credit application risk. 
The evaluations of these models can be found below:

### Naive Random Oversampling

![Screen Shot 2023-01-24 at 11 48 40 AM](https://user-images.githubusercontent.com/112847821/214393885-ae060702-f76a-4e76-b5b5-5f5733001164.png)


* Balanced Accuracy: 0.6299348135255891
* Precision: Low for High Risk loans, and high for Low Risk loans
* Recall = 0.6/0.66 = .909

### SMOTE Oversampling

![Screen Shot 2023-01-24 at 11 54 27 AM](https://user-images.githubusercontent.com/112847821/214395083-0ecebbf2-9793-49e4-bb55-fbda89fda4ca.png)

* Balanced Accuracy: 0.6443721269403855
* Precision: Low for High Risk Loans, High for Low Risk Loans
* Recall = .63/.66= .954

### Undersampling

![Screen Shot 2023-01-24 at 11 56 05 AM](https://user-images.githubusercontent.com/112847821/214395392-e0890033-2264-499d-a2f3-090225484fe9.png)

* Balanced Accuracy: 0.6299348135255891
* Precision: Low for High Risk Loans, High for Low Risk Loans
* Recall = .61/.45 = 1.35

### Combination (Over and Under) Sampling

![Screen Shot 2023-01-24 at 11 58 12 AM](https://user-images.githubusercontent.com/112847821/214395828-9752eaa5-f56e-4d31-bee7-91eb9ba5159e.png)

* Balanced Accuracy: 0.5292150629907619
* Precision: Low for High Risk Loans, High for Low Risk Loans
* Recall = .7/.57 = 1.23

### Balanced Forest Random Classifier

![Screen Shot 2023-01-24 at 11 59 44 AM](https://user-images.githubusercontent.com/112847821/214396131-97f6b139-7bf8-44c2-b18f-e7ac5839a533.png)

* Balanced Accuracy: 0.7877672625306695
* Precision: Low for High Risk Loans, High for Low Risk Loans
* Recall = .67/.91= .736

### Easy Ensemble AdaBoost Classifier

![Screen Shot 2023-01-24 at 12 01 09 PM](https://user-images.githubusercontent.com/112847821/214396346-32952eea-0c10-4213-b858-f363ed6ec1c8.png)

* Balanced Accuracy: 0.9316600714093861
* Precision: Low for High Risk Loans, High for Low Risk Loans
* Recall = .92/.94= .978

## Summary

Primarily, we are looking for a model to use with a high recall and high balanced accuracy. Because of this, we would recommend use of the Easy Ensemble AdaBoost Classifier model, as that provided the highest balanced accuracy and recall by far. 

