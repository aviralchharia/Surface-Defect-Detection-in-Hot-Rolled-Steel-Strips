# Automatic Surface Defect Detection in Hot Rolled Steel Strips

Automatic metallic surface defect inspection has received increased attention in relation to the quality control of industrial products across industries. This project aims to automatically detect metal surface defects such as rolled-in scale, patches, crazing, pitted surface, inclusion and scratches (as depicted in the image below) in Hot-Rolled Steel Strips. The defects are classified into their specific classes via a convolutional neural network (CNN). 

<p align="center">
    <img width="400" height="400" src = 'https://github.com/aviralchharia/Surface-Defect-Detection-of-Hot-Rolled-Steel-Strips/blob/master/Surface%20Defects.png?raw=true'>
</p>

A Convolutional Neural Network (CNN) Model is implemented and trained on the NEU (Northeastern University) Metal Surface Defects Database which contains 1800 grayscale images with 300 samples each of the six different kinds of Surface Defects in Hot Rolled Steel Stips collected in industry. The convolutional neural network model architecture implemented is as below.

<p align="center">
    <img width="420" height="1000" src = 'https://github.com/aviralchharia/Surface-Defect-Detection-in-Hot-Rolled-Steel-Strips/blob/master/CNN%20Model.png?raw=true'>
</p>

The following Model Accuracy & Validation Loss Curves are obtained after 20 epochs.

<p align="center">
    <img width="420" height="180" src = 'https://github.com/aviralchharia/Surface-Defect-Detection-in-Hot-Rolled-Steel-Strips/blob/master/Model%20Accuracy.png?raw=true'>
</p>

<p align="center">
    <img width="420" height="180" src = 'https://github.com/aviralchharia/Surface-Defect-Detection-in-Hot-Rolled-Steel-Strips/blob/master/Model%20Loss.png?raw=true'>
</p>

The results obtained have high test set accuracy and are as as shown below.

<p align="center">
    <img width="420" height="400" src = 'https://github.com/aviralchharia/Surface-Defect-Detection-of-Hot-Rolled-Steel-Strips/blob/master/Results.png?raw=true'>
</p>

The experimental results demonstrate that this method meets the robustness and accuracy requirements for metallic defect detection. Meanwhile, it can also be extended to other detection applications.
