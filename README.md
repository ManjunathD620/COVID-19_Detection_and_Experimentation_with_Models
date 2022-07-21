# COVID-19_Detection_and_Experimentation_with_Models

Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning. Images in dataset were augmented as there were less number of images the dataset. Experimented the dataset on various pretrained models for 10 epochs each and Summarized the results of those experimentation using a bar graph.
# Methdology
![process](https://user-images.githubusercontent.com/82793670/180182856-389bb02b-09d6-46a0-98eb-37fd1bb805e5.jpg)
### 1. Data acquisition
- The dataset we are using is "covid19-xray-dataset-train-test-sets".The dataset is acquired from kaggle website.
### 2. Data preprocessing
- In the data preprocessing stage we normalize the images by dividing each pixel value by 255.Then we resize the images to (224,224) size. 
### 3. Building the model
- In the third step we build a convolutional neural network by using conv2d,maxpool,dropout,flatten and dense layers.Relu is used as activation function for hidden layers and sigmoid is used as activation function for output layer.
### 4. Classification
- In the fourth step we classify the images after training the model.
### 5. Validation
- In the last step we validate the model by evaluating its accuracy and loss on the test dataset
<br>

# Model architecture

| ![download](https://user-images.githubusercontent.com/82793670/180176084-3856f6e7-1de1-437f-b356-7483a792711d.png) | ![3d mocel](https://user-images.githubusercontent.com/82793670/180178081-dba3cb93-ec78-42aa-94b4-d1fb3dca97e3.png) |
------------- | -------------

<br>

# Experimentation
![exper](https://user-images.githubusercontent.com/82793670/180181067-e9f559a3-9fd3-4b29-9c66-d2310a58f119.jpg)

<br>

# TESTING AND RESULTS
![Result](https://user-images.githubusercontent.com/82793670/180181650-59f0e91a-c445-4635-9217-2e7e8ea08f12.jpg)

### <b>--> Custom model was able to achieve an accuracy of 92.50% over 10 epochs .</b>
