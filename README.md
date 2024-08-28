# classification-of-galaxies-using-MobileNet

Project Overview ::

This repository contains the implementation of a galaxy classification model as part of our Spartificial internship project. The goal was to develop a machine learning model that could accurately classify images of galaxies into different categories based on their morphology.

Our approach involves using  deep learning model, specifically MobileNet and SqueezeNet, which are both efficient for such image classification tasks. The models was trained on a dataset of galaxy images (astroNN) , and it performs classification by analyzing the visual features of the input images.

Features

Galaxy Image Classification: Classifies images of galaxies into various categories such as Spiral, Elliptical, and Irregular.
MobileNet Model: Utilizes MobileNet architecture for efficient and accurate classification, balancing performance and computational efficiency.
Confusion Matrix Visualization: Includes visualization of the confusion matrix to evaluate the performance of the model.

Model Architecture

The project leverages the MobileNet architecture, known for its efficiency on devices with limited computational resources. The model was trained and fine-tuned using a large dataset of galaxy images, allowing it to distinguish between different galaxy types effectively.

How to Use

Clone the Repository:
Copy code

git clone https://github.com/AKSHYATA15/classification-of-galaxies-using-MobileNet.git
cd classification-of-galaxies-using-MobileNet

Model Training:

The model can be trained using the provided Jupyter notebook (galaxy_class_mobilenet.ipynb). 

Results

The model achieves a high level of accuracy in classifying galaxies, with detailed performance metrics visualized through the confusion matrix. The final trained model can be used for real-time galaxy classification in various applications, such as in astronomy research and educational tools.

Contributions

This project was a collaborative effort as part of the internship project at Spartificial, with contributions from multiple team members. My primary contribution focused on implementing the MobileNet model, training it on the galaxy dataset, and evaluating its performance.

Future Work
Model Optimization: Further optimization of the model for deployment on mobile and edge devices.
Dataset Expansion: Expanding the dataset to include more galaxy types and increasing the model's generalization capability.
Feature Integration: Integrating the classification model into a web-based or mobile application for real-time galaxy identification.
