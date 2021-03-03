# HAND WRITTEN FORMULA RECONSTRUCTION
This repository contains the RESNET-34 model generation notebook, and the input data preprocessing and model testing notebook.

The RESNET-34 model has been generated using the CROHME-16 dataset consisting of handwritten numbers, and mathematical operators and symbols.

For predicting the input data, preprocessing involves finding contours and reconstruction of the detected numbers and symbols to mimic the properties of the training dataset.

After preprocessing, the generated resnet model is used for predicting the values. These values are stored as a string which describes the detected mathematical expression and calculation of the result is done using certain python built-in functions.
