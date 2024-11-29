# MNIST-Image-Processing-RandomForestClassifier

In this task, the MNIST database was used, which as stated by the creators of the
dataset, “The MNIST database of handwritten digits, available from this page, has a
training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalised and centred in a fixed-size image.”

Once the MNIST dataset was loaded into the notebook, the datasets training data was split further into an training and development(test) sets. So that we now have a training, development(test) and testing(validation) set. 

The RandomForestClassifier was used to create a classification model. 

A tuning parameter was picked, and a unique values was picked to be used on the testing data. 

The confusion matrix  of the testing set was generated using the Random Forest model.

The class the model struggled with most was deduced and the accuracy, precision, recall and f1 scores were computed and interpreted. 
