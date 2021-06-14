# Distracted-driver-detection

In this project a deep learning model is trained to classify the images of the driver captured by dashboard camera into 10 different classes based on their activity.The goal is to predict the likelihood of what the driver is doing in each picture. 

The 10 classes are:

- c0: safe driving
- c1: texting - right
- c2: talking on the phone - right
- c3: texting - left
- c4: talking on the phone - left
- c5: operating the radio
- c6: drinking
- c7: reaching behind
- c8: hair and makeup
- c9: talking to passenger
 
The dataset is obtained from kaggle. Here is the link to the dataset https://www.kaggle.com/c/state-farm-distracted-driver-detection

In this project no pre-trained model is used and a lot of models were trained until we got our best model that is able to achive 99% accuracy on both training and validation data.

### Structure of our model:

![Screenshot (171)](https://user-images.githubusercontent.com/62187533/121958602-7c035300-cd81-11eb-9f85-be6bb155b4e3.png)
![Screenshot (172)](https://user-images.githubusercontent.com/62187533/121958518-62faa200-cd81-11eb-8560-cddef0a08392.png)

### Performance of model:

Results on validation data:

Accuracy = 0.9946492271105827
Precision = 0.9946679011299983
Recall = 0.9946492271105827

Confusion matrix

![dd1](https://user-images.githubusercontent.com/62187533/121957837-9557cf80-cd80-11eb-8f8a-1e3a5c814b16.png)

Some of the results predicted by our model are as follows:

![Screenshot (134)](https://user-images.githubusercontent.com/62187533/121786057-3147d680-cbdb-11eb-907e-ce2b94a22ed0.png)
![Screenshot (135)](https://user-images.githubusercontent.com/62187533/121786058-32790380-cbdb-11eb-8465-19a62dff45cd.png)
![Screenshot (136)](https://user-images.githubusercontent.com/62187533/121786059-33119a00-cbdb-11eb-803f-62ad06bcc661.png)
![Screenshot (137)](https://user-images.githubusercontent.com/62187533/121786060-33119a00-cbdb-11eb-89ca-52c92a2b039f.png)
![Screenshot (138)](https://user-images.githubusercontent.com/62187533/121786061-33aa3080-cbdb-11eb-9bf2-94c47bc04128.png)
![Screenshot (139)](https://user-images.githubusercontent.com/62187533/121786063-3442c700-cbdb-11eb-83ee-ac4344faf3cc.png)

