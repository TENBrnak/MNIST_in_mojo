# CNNs from scratch
This repository will contain my work as I attempt to develop neural networks to solve the MNIST and Fashion MNIST image recognition datasets. It also includes the final version of my seminar paper, which explains the topic of convolutional neural networks in Czech.

I will first try to implement these only using linear algebra libraries (numpy and scipy) and later try to implement these in the new ML-focused language Mojo.
# Inspiration/Source
- heavy inspiration for this work has been taken from the Neural Networks from Scratch by Harrison Kinsley and Daniel Kukiela available at https://nnfs.io/, code for the LayerDense, ActivationReLU, ActivationSoftmaxLossCategoricalCrossentropy and OptimizerSGD classes were taken directly from the book with some but often only limited modifications
- the LayerConvolutional, LayerMaxPooling, LayerFlatten and Network classes were written entirely by me
# Notes for users
## Installation
- all packages required are listed above, namely numpy, scipy and matplotlib (visualization - optional)
- I recommend running in a Jupyter notebook
- pulling the entire repository is also required to get all the accompanying files such as model saves and datasets
## User Guide
- run the _seminarka.ipynb_ notebook mostly sequentially, I recommend skipping the training stages as they take quite long and using the saved models instead
- this notebook is intended for people who are able to read code, it is a proof-of-concept and in no way, shape or form intended for any actual use
