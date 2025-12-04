# Nutrient-deficiency-detection-using-CNN
Nutrient deficiency in banana plants leads to reduced growth and yield. Early detection can help farmers take corrective actions and improve productivity.
This project uses a Convolutional Neural Network (CNN) to automatically classify banana leaf images based on nutrient deficiencies.

Objective
The main objective of this project is to:
* Detect nutrient deficiency in banana plant leaves using image classification.
* Build a deep learning model that can identify deficiencies such as Boron, Calcium, Nitrogen, Potassium, etc.
* Support precision agriculture using AI.

Dataset
Source: kaggle
Classes: boron  calcium	healthy  iron  magnesium  manganese  potassium	sulphur  zinc
Loss Function: Categorical Cross Entropy
Optimizer: Adam
Metrics: Accuracy

Tools and Libraries
Python,Tensorflow/Keras,Matplotlib,Google colab

Results
Model Training Accuracy: 60%

Performance Graphs

<img width="1004" height="374" alt="Unknown" src="https://github.com/user-attachments/assets/008c95ed-5e3e-47f0-b132-b9f6744d126a" />

Future Improvement

Plan to test with DINOV2 model to capture high level lesf texture patterns
