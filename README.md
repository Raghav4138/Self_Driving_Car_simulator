# Self-Driving Car Simulator

Welcome to the Self-Driving Car Simulator project!

This project is dedicated to the development of a machine learning model that leverages real-time data from the Udacity simulator to predict steering angles. The underlying model is constructed using NVIDIA's TensorFlow CNN architecture, ensuring robust and accurate predictions.

## Getting Started

To use this simulator, follow these steps:

1. Ensure Anaconda is installed on your system.
2. Create a virtual server and environment using Anaconda.
3. Execute the model to observe its predictions in action.

## Usage

Refer to the included video file for a detailed demonstration of the project in action.

Feel free to explore, contribute, and enhance the capabilities of our Self-Driving Car Simulator. Your involvement is crucial to the continuous improvement of this project.

## Using Different Models

In this repository, you'll find a dedicated 'models' folder containing various pre-trained models. You can easily incorporate these models into the project by editing the model instantiation in the 'drive.py' file.

To make the necessary adjustments, navigate to line 52 of the 'drive.py' file and modify the model instantiation line accordingly. Each model in the 'models' folder has been created using different parameters and dropout configurations, allowing you to experiment with different architectures.

We recommend starting with the 'model.h5' file, as it represents the best-performing model based on our experimentation. However, feel free to explore other models in the 'models' folder to observe how different configurations impact the performance of the self-driving car simulator.
