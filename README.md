## Deep Dream
### [[Notebook (InceptionV3)]](DeepDream/DeepDreamInceptionV3.ipynb)
### [[Notebook (GoogLeNet)]](DeepDream/DeepDreamGoogLeNet.ipynb)

Two different Deep Dream implementations, one using InceptionV3 and preprocessing the image by adding inceptions (downscaled and blured samples) and another using GoogLeNet with the raw image. Both of them use torch hooks.

## Psychedelic Bunny Rabbit
### [[Notebook]](PsychedelicBunnyRabbit/PsychedelicBunnyRabbit.ipynb)

Neural Style Transfer in Pytorch over a nice bunny rabbit. [[README]](PsychedelicBunnyRabbit/README.md)

## Bob Ross's paintings segmentation
### [[Notebook]](BobRoss/BobRoss.ipynb)


UNet semantic segmentation of Bob Ross paintings.
Still in progress. Aimed to understand:

- FCNN
- Train a small Net with small data (dataset has ~200 samples)
- Struggle with hyperparams

## Fast Neural Style Transfer
### [[Notebook]](FNST/FNST.ipynb)

Checking the Fast Neural Style Transfer from [ONNX Zoo Pretrained Model](https://github.com/onnx/models/tree/master/vision/style_transfer/fast_neural_style).

## Paul the Octopus
### [[Notebook]](PaulTheOctopus/PaulTheOctopus.ipynb)

Analyzing football results and use with XGBoost to predict results. Still in progress, results right now are pretty bad, I have some ideas about adding synthetic features and stuff. 

## Digit recognizer
### [[Notebook]](DigitRecognizer/DigitRecognizer.ipynb)

Training a CNN to recognize handwritten numbers using Sklearn's **digits** dataset with Pytorch. This is multi-label classification task and aims to understand different tools and visualizations for classification such as:

- visualize distribution per class (for train and validation split also)
- sklearn's classification report
- sklearn's confusion matrix

## Make Moons
### [[Notebook]](MakeMoons/MakeMoons.ipynb)

Training a NN using Sklearn's **make_moons** dataset with Pytorch to visualize non-linear predictions given by a Neural Network.

## Iris Random Forest Classifier
### [[Notebook]](IrisRandomForestClassifier/Iris.ipynb)

Using Grid Search - Pipelines and Random Forest in Sklearn to classify the Iris dataset.
