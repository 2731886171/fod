# Instruction

## Preparison

You can skip following two steps if you don't want to build virtual envrionment.

1. `python3 -m venv ~/.virtualenv/opencv`

1. `source ~/.virtualenv/opencv/bin/activate`

Install neccessary packages.

1. `pip install --upgrade pip`

1. `pip install scikit-build`

1. `pip install opencv-python`

1. `pip install jupyterlab`

## Start Notebook

`jupyter lab`

## Comments

The end to end flow is: 

1. Read the image.

1. Conver to grayscale.

1. Gaussian Filter.

1. Calculate the Y gradient.

1. Gaussian Filter.

1. Gaussian Adaptive Threshold.

1. Edging and Dilating.

1. Write the output to disk.
