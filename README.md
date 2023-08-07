# Detecting Lung Disease Using Machine Learning Techniques

## Datasets
- [Sample dataset](https://www.kaggle.com/nih-chest-xrays/sample)
   - Contains 5,606 images (1024x1024) and class labels for a reduced version of the full dataset.
   - 15 classes, including 14 diseases and "No findings."

- [Full dataset](https://www.kaggle.com/nih-chest-xrays/data)
   - Includes 112,120 images (1024x1024) with bounding box coordinates and class labels for 15 classes.

## Algorithms and Techniques
- CNN (Convolutional Neural Network)
- Spacial Transformer
- VGG finetuning
- Capsule Network

## Models
- Vanilla CNN
![Vanilla CNN](./images/vallina.jpg)

- Optimized CNN
![Optimized CNN](./images/Optimized%20CNN.jpg)

- Capsule Network (CapsNet)
![CapsNet](./images/CapsNet.jpg)

## Installation
- [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html) with [Python 3](http://docs.python-guide.org/en/latest/starting/install3/linux/)
```sh
$ sudo apt-get update
$ sudo apt-get install python3-pip python3-dev
$ pip3 install --upgrade pip
$ pip3 install jupyter
```

- [Tensorflow](https://www.tensorflow.org/install/install_linux) for GPU
```sh
$ pip3 install tensorflow==1.8.0     # Python 3.n; CPU support (no GPU support)
$ pip3 install tensorflow-gpu==1.8.0 # Python 3.n; GPU support 
```

- [Keras](https://keras.io/#installation) for GPU
```sh
$ pip3 install keras
```

- Libraries needed: numpy, pandas, seaborn, matplotlib, opencv, pickle, sklearn, tqdm, glob

## Important
- Run [Data preprocessing](./Data%20preprocessing%20-%20SampleDataset.ipynb) first to create preprocessing file in the Sample dataset before running other notebooks for the Sample dataset.
