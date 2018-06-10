# ISIC2018
This is from the ISIC 2018 challenge. To make the code work that is shown below you must create folders inside the train and test folder for each of the class names.


https://challenge2018.isic-archive.com/

The first model, in the first commit had a validation accuracy of 0.83386

The second model used Inception V3 weights for transfer learning but only achieved an accuracy of .65 of validation data. This may be because I did something wrong with the freezing and training of layers.


The .py file is an edited version of the same file in the repo below. It allows me to run the network on new images and not the mnist data set.

https://github.com/XifengGuo/CapsNet-Keras
