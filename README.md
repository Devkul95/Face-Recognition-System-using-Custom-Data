# Face-Recognition-System-using-Custom-Data
A Face Recognition System implemented using Convolutional Neural network by using the VGG16 model pretrained by the imagenet weights.
## Steps to run:
* "Using camera to create a dataset of images.ipynb" create custom dataset
* Run "face recognition using vgg16.ipynb" to create the model, After running the model a ben.h5 named model will be saved.
* Run Face Recognizer.ipynb to recognize the faces that were provided in the dataset.
## Methodology
### 1. Importing Various Modules
### 2. Preparing Data
* Making the functions to get the training and validation set from the Images
* Visualizing Some Random Images
* Extract all the images and crop into (224,224,3)
* Label Encoding the Y array (i.e. Ben Affleck->0, Devkul->1 etc...) & then One Hot Encoding
* Splitting into Training and Validation Sets
* Data Augmentation to prevent Overfitting

## MODELLING
* Importing the Vgg16 model
* Change the softmax input
* Training the Model
* Evaluating the Model Performance
## VISUALIZING PREDICTIONS ON THE VALIDATION SET
## Web Cam Detection
