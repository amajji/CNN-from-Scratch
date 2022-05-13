# Multiclass classification.
Data scientist | [Anass MAJJI](https://www.linkedin.com/in/anass-majji-729773157/)
***

## :monocle_face: Description
- This project aims to implement a multi-class classification model. we have four classes with a minority class (less than 1%), 
so we are in the case of unbalanced classes. We used regularization methods in order to penalize the errors made on this minority class.
The model is trained to predict around 4 different class. </br>

 

## :rocket: Repository Structure
The repository contains the following files & directories:
- **Dataset directory:** It contains a data pre-processing notebook where the train.csv file is used for training 
the model. Il contains also the predictions of test.csv dataframe.
- **model_weights:** It contains all the weights of the models : one-hot-encoder, target encoder, random forest model.

- **App directory:** Code for the web application that was developed for the model deployment. It contains Flask API code for the Back-End,
and HTML/CSS/Javascript code for the Front-End.


![](last_gif.gif)

## :chart_with_upwards_trend: Performance & results

- The test dataset contains **25 000 samples**. Each sample contains many features, and its corresponding label.

- The model used for this multi-class classification task is a **Random Forest** model.

- The metric used to measure the model's performance is **F1-score**. After testing the model, I obtained a test F1-score of **72 %**




---
## :mailbox_closed: Contact
For any information, feedback or questions, please [contact me][anass-email]





[anass-email]: mailto:anassmajji34@gmail.com
