# AppleClassifier

Binary classifier with class Apple and Not-Apple usiing pre-trained Densenet-121.

## Dataset Properties

* Total Number of images: 13,882 with one fruit per image.
* Training set size: 11,026 (3,372 Apples and 7,654 Not-Apples)
* Validation set size: 2,856 (1,100 Apples and 1,756 Not-Apples)
* Classes: Apple and Not-Apple
* Not-Apple includes apricot, avacado chestnut, eggplant, banana, blueberry, peach, orange, guava, lychee, and lemon.

The dataset used is a subset of data available here: https://www.kaggle.com/moltean/fruits.

## How to use this

### Setup Requirements
* Pytorch 1.8.1 cuda 11.1
* Python 3.9.2 Windows 10
* Numpy
* Matplotlib
* Pandas
* Seaborn
* Jupyter Notebook (Classifier.ipynb and Test.ipynb)

### Usage

The images to be predicted must be included in the Apple_Notapple_data/Test

The model is saved as AppleClassifier.pth

The model is trained with weights given as apple_classifier.pt

Classifier.ipynb contains model creation, taining and validation.

After adding images in Apple_Notapple_data/Test, run Test.ipynb.

Note: 20 images already added in Apple_Notapple_data/Test.
