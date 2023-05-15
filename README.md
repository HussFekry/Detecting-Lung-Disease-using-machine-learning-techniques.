# Detecting-Lung-Disease-using-machine-learning-techniques.
# Datasets
# [Sample dataset](https://www.kaggle.com/nih-chest-xrays/sample)
* File contents: this is a random sample (5%) of the full dataset:
 sample.zip: Contains 5,606 images with size 1024 x 1024
 sample_labels.csv: Class labels and patient data for the entire dataset
* Class descriptions: there are 15 classes (14 diseases, and one for "No findings") in the full dataset, but since this is drastically reduced version of the full dataset, some of the classes are sparse with the labeled as "No findings": Hernia - 13 images, Pneumonia - 62 images, Fibrosis - 84 images, Edema - 118 images, Emphysema - 127 images, Cardiomegaly - 141 images, Pleural_Thickening - 176 images, Consolidation - 226 images, Pneumothorax - 271 images, Mass - 284 images, Nodule - 313 images, Atelectasis - 508 images, Effusion - 644 images, Infiltration - 967 images, No Finding - 3044 images.
#[Full dataset](https://www.kaggle.com/nih-chest-xrays/data)
* File contents:
 images_00x.zip: 12 files with 112,120 total images with size 1024 x 1024
 README_ChestXray.pdf: Original README file
 BBox_list_2017.csv: Bounding box coordinates. Note: Start at x,y, extend horizontally w pixels, and vertically h pixels
 Data_entry_2017.csv: Class labels and patient data for the entire dataset
* Class descriptions: there are 15 classes (14 diseases, and one for "No findings"). Images can be classified as "No findings" or one or more disease classes: Atelectasis, Consolidation, Infiltration, Pneumothorax, Edema, Emphysema, Fibrosis, Effusion, Pneumonia, Pleural_thickening, Cardiomegaly, Nodule Mass, Hernia.

# Algorithms and Techniques
* CNN
* Spacial Transformer
* VGG finetuning
* Capsule Network

# Vanilla CNN
![](./images/vallina.jpg)

#Optimized CNN
![](./images/Optimized%20CNN.jpg)

#CapsNet
![](./images/CapsNet.jpg)

# Installation
# [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/install.html) with [python3](http://docs.python-guide.org/en/latest/starting/install3/linux/)
```sh
$ sudo apt-get update
$ sudo apt-get install python3-pip python3-dev
$ pip3 install --upgrade pip
$ pip3 install jupyter
```
# [Tensorflow](https://www.tensorflow.org/install/install_linux) for GPU
```sh
$ pip3 install tensorflow==1.8.0     # Python 3.n; CPU support (no GPU support)
$ pip3 install tensorflow-gpu==1.8.0 # Python 3.n; GPU support 
```
# [Keras](https://keras.io/#installation) for GPU
```sh
$ pip3 install keras
```
# Lib needed
-numpy , pandas, seaborn , matplotlib , opencv , pickle , sklearn , tqdm , glob

# Important
-Run [Data preprocessing](./Data%20preprocessing%20-%20SampleDataset.ipynb) first to create preprocessing file in Sample dataset before run other notebook for Sample dataset.  



