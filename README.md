# Solar-Panel-Defect-Detection
This project uses Convolutional Neural Networks (CNNs) to automatically detect defects in solar panels. The system classifies an input image into six classes:
a) Bird-drop
b) Clean
c) Electrical-damage
d) Snow-Covered
e) Dusty
f) Physical-Damage
The goal of this project is to automate manual inspection, increase fault-detection accuracy, and help in predictive maintenance of photovoltaic (PV) systems.
Dataset:
The dataset consists of high-resolution images of solar panels captured in different environmental and operational conditions.
Class	        Number of Images
Bird-drop	        191
Clean	            193
Electrical-damage	103
Snow-Covered	    123
Dusty	            190
Physical-Damage	    69
Data was then augmented using rotation, zoom, shifting, shearing, and flipping to balance the classes.
Models:
Multiple pre-trained CNN architectures were fine-tuned:
1. ResNet50
2. VGG16
3. InceptionV3
4. EfficientNetB0
5. MobileNetV2
Each model was trained using transfer learning with added dense layers for classification.
Objectives:
Train multiple CNNs on the solar panel dataset
Evaluate each model's accuracy and performance
Use the best-performing model to classify images into 6 defect types
Provide an easy-to-use inference script for real-time testing
Technologies & Tools:
Python
TensorFlow / Keras
OpenCV
NumPy / Pandas
Matplotlib
Google Colab / GPU