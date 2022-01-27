# drug-prediction
I have collected data about a set of patients, all of whom suffered from the same illness. During their course of treatment, each patient responded to one of 5 medications, __Drug A__, __Drug B__, __Drug c__, __Drug x__ and __y__.  Part of our job is to build a model to find out which drug might be appropriate for a future patient with the same illness. The feature sets of this dataset are __Age__, __Sex__, __Blood Pressure__, and __Cholesterol of patients__, and the target is the drug that each patient responded to.

It is a sample of binary classifier, and I can use the training part of the dataset to build a decision tree, and then use it to predict the class of a unknown patient, or to prescribe it to a new patient. Then we use the trained decision tree to predict the class of a unknown patient, or to find a proper drug for a new patient.

![](https://github.com/KhazarHaydarli/drug-prediction/blob/main/confusion.png)

My 1 class is False but other classes are True in my Confusion Matrix
