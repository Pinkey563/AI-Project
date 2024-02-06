# AI-Project

_ This is the AI project during the first semester of my 3rd year at university

# Head detection and face attribute classification

_ This project focuses on detecting head in a random picture using the YOLOv8 model and then classify the face attributes that appear using ResNet50 model.

## 🎯 Objective
_ In the context of increasing demands for security and personal information management, facial recognition and analysis have become powerful tools, helping to accurately identify and track individuals' behavior in real time. 

_ At security points such as airports or banks, restaurants, supermarkets,... this system can quickly verify identity, and support the detection and prevention of crimes. In the public sector, face extraction technology helps improve crowd monitoring and management, while also supporting search in emergencies.

## 📦 Data Source
_ Our group finds data on Kaggle and then labels the images ourselves to train the model

## 🚀 Included files

1. Train_yolov8

_ This is the model used to detect the head that appears on the given picture

_ This can be modified from the original one(https://blog.roboflow.com/how-to-train-yolov8-on-a-custom-dataset/)

2. Resnet

_ This is the model used to classify the attributes on the detected head

3. Connect_2_models

_ This is the code used to connect 2 models (Yolov8 and ResNet50) 

4. best/last.pt

_ The file contains the best/last epoch of the training process
    
## ⚙️ Installation

1. **Requirements**:

    - Python 3.x
    - Libraries: yolov8, ...

2. **Setup**:

    ```
    _ Clone this repository
    _ Change the link path in the code to your own path
    ```
