# CryoBioData

This repository contains unlabelled data provided by the Cryobiology Research Institute.
For training, validation and testing use images from the corresponding folders.

Ground truth count labels can be found in *labels.xlsx* file. To obtain the number of cells on a certain image, sum up all the 16 numbers from different subsquares.
**Do not forget to replace -100 values with np.nan in advance!!!**