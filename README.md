# Identifying Lung Diseases through Machine Learning Approaches

## Overview
This project focuses on utilizing machine learning techniques to detect lung diseases effectively. By analyzing medical images of lung X-rays, the goal is to create accurate and efficient models that can identify various lung conditions, including diseases and "No findings."

## Datasets
Two datasets are used for this project:

- [Sample dataset](https://www.kaggle.com/nih-chest-xrays/sample):
   - This dataset contains 5,606 images (1024x1024) and corresponding class labels for a reduced version of the full dataset.
   - There are 15 classes, consisting of 14 different diseases and a class for "No findings."

- [Full dataset](https://www.kaggle.com/nih-chest-xrays/data):
   - The full dataset comprises 112,120 images (1024x1024) with bounding box coordinates and class labels for the same 15 classes.

## Techniques and Algorithms
To accomplish the task of lung disease detection, several machine learning techniques and algorithms are employed in this project:

- CNN (Convolutional Neural Network): A powerful deep learning architecture well-suited for image classification tasks.
- Spacial Transformer: A module that enables the network to learn spatial transformations, leading to improved feature extraction.
- VGG Finetuning: Fine-tuning a pre-trained VGG model to enhance performance on the specific classification task.
- Capsule Network (CapsNet): An innovative neural network architecture designed to handle hierarchical spatial relationships and improve representation learning.

## Models
This project showcases three primary models:

1. Vanilla CNN: A straightforward implementation of the Convolutional Neural Network.
   ![Vanilla CNN](./images/vallina.jpg)

2. Optimized CNN: A refined and optimized version of the CNN model.
   ![Optimized CNN](./images/Optimized%20CNN.jpg)

3. Capsule Network (CapsNet): An advanced neural network architecture with capsule layers for improved feature representation.
   ![CapsNet](./images/CapsNet.jpg)

## Installation and Dependencies
To replicate this project, follow the installation steps below:

1. Install Jupyter Notebook with Python 3.
```sh
$ sudo apt-get update
$ sudo apt-get install python3-pip python3-dev
$ pip3 install --upgrade pip
$ pip3 install jupyter
```

2. Install TensorFlow for GPU or CPU support.
```sh
$ pip3 install tensorflow==1.8.0     # Python 3.n; CPU support (no GPU support)
$ pip3 install tensorflow-gpu==1.8.0 # Python 3.n; GPU support 
```

3. Install Keras for GPU support.
```sh
$ pip3 install keras
```

4. Install necessary libraries: numpy, pandas, seaborn, matplotlib, opencv, pickle, sklearn, tqdm, glob.

## Data Preprocessing
Before running other notebooks for the Sample dataset, it is essential to execute Data preprocessing to create the preprocessing file. This step ensures proper data preparation for subsequent analyses.

By employing these techniques and models, this project aims to contribute to the early detection and accurate identification of lung diseases, thereby improving patient outcomes and healthcare management.
