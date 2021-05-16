* In this project we will be working on Covid detection using CNN. The historical data that we will be using is Covid chest X-Rays. 

* The pre trained model that we will be uing is VGG-16. The accuracy that i am receiving is around 85 %

* The another agenda of this project is to visualize the Class Activation maps. The class activation map is basically what ml algorithem has learned in the last convolution layer. 
    i.e If the model says the image of chest is COVID, why is the image covid ??? This is where we use GRAD-CAM (Gradient - Class Activation Map) 
    
    * This grad-cam function returns the heat map, which later is mapped on the input xray, with this we can determine which area in chest has COVID-19

* NOTE : "https://www.dropbox.com/s/e1r2laj50nh4tez/COVID-19_Radiography_Dataset.zip?dl=0" you can download the data set using linix command !wget. 
* To Run the code you can download the jupyter note book file and upload directly to your colab
