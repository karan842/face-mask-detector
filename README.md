# Face Mask Detector :mask:
by Live Camera 

- Detecting masked or unmasked faces by live camera with percentange of mask occupation

# About Project:
 This an **Artificial Intelligence** based project in which we can detect person's faces by live camera and system can predict that person weared a mask or not. A programming language that I used in this project is Python. Where I build a predective model with the help of Neural Networks (Deep Learning). Dataset contains two classes that means two type of images such as **With Mask** and **Without Mask**
 
# Overview:
 1. Importing machine learning libraries - Tensorflow, Keras and Sklearn
 2. Loading dataset and divding into two categories - With Mask and Without Mask
 3. Converting Categories into numbers by LabelBinarizer
 4. Splitting data into train, test and split
 5. Data Augmentation by ImageDataGenerator
 6. Creating neural network with MobileNetV2, and connected entire layers
 7. Compiling the model Adam optimizer and binray_cross entropy loss
 8. Using callbacks while model training to avoid overfitting
 9. Evaluating the model by classification report and confusion matrix
 10. Visualized model accuracy and val_loss
 11. Serializing the model and implementing into python code for live camera 
 12. Using OpenCv and imutils for live implementation

## Live Demo: https://twitter.com/KuchBhiKaran/status/1482999558536036352?t=RgL5Rt0QA9uZgXHCNAHKuQ&s=19
