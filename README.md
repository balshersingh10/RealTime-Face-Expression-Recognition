![RealTime-Face-Expression-Recognition](https://i1.wp.com/sefiks.com/wp-content/uploads/2018/01/kid-expressions-cover.png?resize=560%2C9999&ssl=1)
# RealTime-Face-Expression-Recognition
We obtained the Face Expression Dataset from Kaggle's website and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of VGG model with adding Top layers to it.
## A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are:
- Image pixels which are reshaped to (48x48x3)
## B. Model Selection
Neural Network with:
* epochs = 80, 
* batch_size = 32, 
* Optimizer = SGD
## C. Training the models with Data
The data taken is from **https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data**
## D. Taining Data and Testing Data
Data is divided using custom function split_for_test.
## For Realtime Expression Recognition, CV2 is used.
- It uses webcam and detects face using 'haarcascade_frontalface_default.xml'.
- With a click of spacebar, you can capture frame of webcam and the model will predict after processing the image.
- The outputs are : ANGRY, DISGUST, FEAR, HAPPY, SAD, SURPRISE, NEUTRAL.
- You can quit by pressing and holding 'q'.
# Result =>
- It has Train accuracy of nearly 99.79%. 
- Test Accuracy of nearly 67.75%. <br />
## Files included in repository are:
- **Face_Expression_Recognition.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **Real_Time_Prediction.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **haarcascade_frontalface_default.xml**
- **data folder(Contains FER2013.csv file)**
- **saved_model/my_model(Contains saved model trained by me)**  <br />
