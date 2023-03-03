# tfcatflap-training

## Purpose
In this repository the model for [https://github.com/swisscheese38/tfcatflap](https://github.com/swisscheese38/tfcatflap) was trained. The pictures have been taken by a Raspberry Pi camera that's mounted on a Sureflap Pet Door. At first the images were taken every time that the pet door itself was unlocked (using a micro switch attached to the locking mechanism). After having trained the model with roughly 50 images it was able to detect cat snouts and the locking/unlocking had been switched to be done by the Raspberry Pi and no longer the cat flap itself. You can find this training data in the folders [train](train), [validate](validate) and [test](test). Every time the cat flap was unlocked for the next three months another picture was taken and the model had been trained again with about 500 pictures.

## Training the model
Checkout the Jupyter notebook (using Colab) I used to create the model: [train.ipynb](train.ipynb)

## Play around with the model
There's a different Jupyter notebook that you can use to try out different sources of data (images, videos) for the model to detect objects in: [tryoutmodel.ipynb](tryoutmodel.ipynb)
