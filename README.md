# CryoBioData

## Brief repository description

This repository contains unlabelled data provided by the Cryobiology Research Institute.
For training, validation and testing use images from the corresponding folders.

Ground truth count labels can be found in *labels.xlsx* file. To obtain the number of cells on a certain image, sum up all the 16 numbers from different subsquares.
**Do not forget to replace -100 values with np.nan in advance!!!**

## Prompts-to-use

Below are some useful prompts that can be used via Windows Command Prompt to work with the repository.

To download the images when working in Google Colab / Jupyter Notebook, enter the prompt below into the code cell:
```bash
!git clone https://github.com/EugenTheMachine/CryoBioData.git
```

For Windows Command Prompt use:
```bash
git clone https://github.com/EugenTheMachine/CryoBioData.git
```