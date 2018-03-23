# Facial-Expression-Recognition
The main objective  of this project is  recognition of emotions based on different facial expressions.
Here, we have used  Cohn-Kanade data set (http://www.pitt.edu/~emotion/ck-spread.htm).  
It is used for explorations and training.

The Cohn-Kanade is a data set of face images labeled for 7 expressions/emotions :
* Anger
* Contempt
* Disgust
* Fear
* Happiness
* Sadness
* Surprise

The solution consists of versatile classifiers including Decision Tree, Random Forests, Support Vector Machines, DT based Binary Classifier, simple hybrid classifier.

Performance results, estimated by cross validation tests: 

* Multi-class Support Vector Machines (radial kernel, kernlab): 96.5% (st. deviation = 0.4%)
* Multi-class Support Vector Machines (linear kernel, e1071): 95.4%
* Decision Tree based classifier: 86.49% 

