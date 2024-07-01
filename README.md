# 📷Visual Object Recognition Program
- Project Duration : 2023.01 ~ 2023.02
- Project Description : Embedded system designed for recognizing and defining objects captured by a camera using deep learning-trained image data. (data : Imagenet_2017).
---
Constructed both the embedded system and the computational pipeline, developing a Python algorithm for image classification in a TensorFlow session, and interpreting results in LabVIEW program designed for image reception.

## LabVIEW
- Output : Visual Object Recognition
- When the camera captures an object, the program will detect the object and classify it based on the training image data.
![image](https://github.com/langsung01/Visual-Object-Recognition-Program/assets/174301247/12ff6661-12d5-4d83-ba76-d44cd6589675)
- ** Reference : https://www.youtube.com/watch?v=szxegYAev7M&ab_channel=NationalInstrumentsKoreaAE
- -> Referring to VI Code, Writte and Complete Python Algorithm
### Step1. Connect the Camera
![image](https://github.com/langsung01/Visual-Object-Recognition-Program/assets/174301247/9f9e9f1c-5ce3-4c1a-ba4a-781f520fef02)

### Step2. while obtaining images(Default)
![image](https://github.com/langsung01/Visual-Object-Recognition-Program/assets/174301247/b5e176bf-690c-4f6b-a0b6-2a4ec188821e)

### Step3. sub Vi
![image](https://github.com/langsung01/Visual-Object-Recognition-Program/assets/174301247/e67be589-ed50-4dfe-8258-21d07d00270d)
- converting the data type, which is used to store images and is different from the data type handled in Python, into a data type that can be used for both.

### Step4. Object Recognition and Classification using Python Algorithm
![image](https://github.com/langsung01/Visual-Object-Recognition-Program/assets/174301247/9ea47332-b82c-4263-b645-fa510c15aa64)
