# Context
This project, focuses on applying Machine Learning (ML) in the field of Time Domain Astronomy. We specifically target automating or facilitating the alert scanning process in astronomical observations using neural networks.

# Objective
Our goal is to train models that can analyze image data and metadata from ZTF alert packets, similar to human observation, but with higher consistency and speed.

# Implementation Details
## Data Preparation
### Data Cleaning: Identifying non-numeric data and missing values, followed by their removal.
### Data Normalization: Scaling different ranges of data between 0 and 1.
### Metadata Selection: Choosing the most informative metadata based on the data distribution relative to the classes.
## Model Architecture
### BTS Model: A multi-input neural network combining CNN for image data and a standard neural network for metadata.
### ResNet-Inspired Model: Exploring advanced architectures for potential performance gains.
## Training and Evaluation
### Data Generators: To efficiently handle large datasets.
### Callbacks: Including Early Stopping, Learning Rate Reduction, and Model Checkpoints.
### Training Process: Utilizing class weights to address imbalances and training with various configurations.
### Performance Metrics: Evaluating models based on accuracy, precision, recall, F1 score, and AUC.
## Research and Development
### Model Research: Inspired by existing models and tailored to our specific requirements.
### Hyperparameter Tuning: Leveraging WandB for optimizing model parameters.
### Experimentation: Testing different architectures and strategies to enhance model performance.
