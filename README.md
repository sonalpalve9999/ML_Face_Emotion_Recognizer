# ML_Face_Emotion_Recognizer
Facial Emotion Recognition App  is an Application taken in Consideration  for actually determining the human emotions through training a certain machine learning model .
So, In these project we actually build a web-App where we can detect facial emotions by just capturing the image from the webcam which gets active while live streaming video turns on , on our web-cam.
These Application is build using the libraries like : 
1.Tensorflow
2.Keras
3.Numpy 
4.Flask
5.Opencv
These App is basically build with purpose of helping teachers let know which student is feeling nervous , sad , happy or disgust in online classes and can keep a record of feedbacks of students as their emotions.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Needed Improvement

The model embedded in Web-Application is Successful for predicting the neutral , happy and sad faces , (i.e at most 60% Accuracy has been achieved by the model)
Improvement is needed in training the model to recognize the sad , disgust , fear emotions .
Frontend has been styled in a very simple manner with no options , So Improvement is needed in Frontend Styling with more options .
Can upgrade some functionalities like downloading the Feedback .So as to keep the permanent records .

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Data Collection and Data Visualization

The dataset is been obtained by the website Kaggle .
Name : FER(2013)
Kaggle : https://www.kaggle.com/msambare/fer2013

License : Database: Open Database, Contents: Database Contents
Fer2013 contains approximately 30,000 facial RGB images of different expressions with size restricted to 48×48. 
the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Web-App Architecture :

Directory Structure : 
Index.html : Homepage of An Application
App.py : Containing the code for the Web-Application Deployment
Emotion_Detection.py : Neural Network Implementation for training the model                                   through fer2013 dataset
Fer.h5 : Used for saving the trained model Architecture 
Fer.json : for saving the loaded weights 
Functioning :  whenever the person goes on the web Application through link 
First the camera gets onn , captures the face , i.e In input ,the app gets feed by the video after that the video gets splitted into the individual frames , as soon as the frames get feeded to trained model , it actually starts working on it and try to match the parameter with all of the expression, now the one with whom the parameter has been matched ,that expression is been displayed on the screen .

