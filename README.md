# tfcatflap-training
Work in progress

## Purpose
In this repository the model for `https://github.com/swisscheese38/tfcatflap.git` is trained. The pictures have been taken by a Raspberry Pi camera that's mounted on a Sureflap Pet Door. At first the images where taken every time that the pet door itself was unlocked (using a micro switch attached to the locking mechanism). After having trained the model with roughly 50 images it was able to detect cat snouts and the locking/unlocking had been switched to be done by the Raspberry Pi and no longer the cat flap itself. Ever since the cat flap is taking more and more pictures so I'll be able to better train the model in the future.

## Training the model
Checkout the Jupyter notebook (using Colab) I used to create the model: [train.ipynb](train.ipynb)

## Play around with the model
There's a different Jupyter notebook that you can use to try out different sources of data (images, videos) for the model to detect objects in: [tryoutmodel.ipynb](tryoutmodel.ipynb)
