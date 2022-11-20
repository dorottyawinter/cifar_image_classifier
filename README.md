## Project: CIFAR Image Classifier
### Project Overview

In this project, I build an image classifier and object detection system using PyTorch. I train and evaluate the classifier on CIFAR-10 benchmark dataset.

### Dependencies

This project requires **Python 3.9** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/) (>= 1.20.3)
- [matplotlib](http://matplotlib.org/) (>= 3.4.3)
- [Pytorch](http://scikit-learn.org/stable/) (>= 1.13)
- [Torchvision](http://pandas.pydata.org) (>= 0.14)

### Running Instructions

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Here are the classes in the dataset:
- airplane										
- automobile										
- bird										
- cat										
- deer										
- dog										
- frog										
- horse										
- ship										
- truck										

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. **Automobile** includes sedans, SUVs, things of that sort. **Truck** includes only big trucks. Neither includes pickup trucks.

### Licensing, Author, Acknowledgements
This project was completed as part of the [Udacity Intro to ML with Pytorch Program](https://www.udacity.com/course/intro-to-machine-learning-nanodegree--nd229).