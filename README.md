# Machine Learning Engineer Nanodegree
# Deep Learning
## Project: CNN Project to Recognize Dog Breeds

### Project Overview

This is a project I worked on as part of my Udacity Machine Learning Engineer Nanodegree. In this project, I build a Convolutional Neural Networks (CNN) to predict the breed of a dog in a given photo. In the latter half of the project, you will find an app I built that allows for human image inputs that will predict the dog breed he/she most resembles.

### Data

The training data for this project is located [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). This dataset contains 133 different breeds of dogs and is already split into train, test, and validation sets. Place the training, testing, and validation datasets in the `dogImages` folder.

### Instructions

If you want to run this code on your local computer, you'll also need to download the bottleneck features found [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz). 

It is recommended that an environment is set up in advance for this project to ensure that the proper versions of the required libraries are present.


 __Mac/OSX__:
```
	conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

__Linux__:
```
	conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

__Windows__:
```
	conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
```

Command to open Jupiter Notebook:

```
	jupyter notebook dog_app.ipynb
```