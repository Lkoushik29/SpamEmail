# SpamEmail

This is my project on email spam detection using Classification Techniques in machine learning. I have taken a dataset from kaggle and processed it and removed unwanted columns from the dataset. 

The dataset link is "https://www.kaggle.com/datasets/shantanudhakadd/email-spam-detection-dataset-classification"

Then using visualizing tools like countplot of the ham and spam percentage in the dataset.Histogram for the frequency detection for the length of text from each messsage and made ham/spam as 0/1 in dataset.

![image](https://github.com/Lkoushik29/SpamEmail/assets/91585444/f4b395a3-993f-41d7-958d-c3589ad4acc4)

![image](https://github.com/Lkoushik29/SpamEmail/assets/91585444/ffb37ac1-caa7-4373-a764-95df19b43ac1)

![image](https://github.com/Lkoushik29/SpamEmail/assets/91585444/562f8219-c188-431b-8c76-66db89914a0d)


Coming to the methods i used 3 techniques MLPClassifier, Multinomial Naive Bayes,  Bernoulli Naive Bayes. using proper libraries imported the required model libraries and train and test parameters.


Calculated the confusion matrix for every method and and accuracy, precision, recall, F1 score and thenn compared them in a heatmap.

![image](https://github.com/Lkoushik29/SpamEmail/assets/91585444/b69eebe4-de29-4071-aa6a-e18e380d0c34)


Conclusion is that Multi layer perceptron(MLP) of neural networks algorithm has shown best results in detection of spam mails so far.
