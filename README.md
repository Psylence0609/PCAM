# PCAM Data Classification

This repository contains a project for classifying images in the PatchCamelyon (PCAM) dataset. The goal is to predict whether a histopathology patch contains metastatic tissue.

## Dataset

![PCAM Dataset Image](https://production-media.paperswithcode.com/datasets/pcam_Dj5Hqa9.jpg "PCAM Dataset Image")


The **PatchCamelyon (PCAM)** dataset consists of small image patches extracted from histopathology slides. Each image patch is labeled as either containing metastatic tissue (positive) or not (negative). The dataset is commonly used for research in medical image classification.

- **Image size**: 96x96 pixels
- **Channels**: RGB
- **Classes**: 
  - `0`: No metastatic tissue (Negative)
  - `1`: Contains metastatic tissue (Positive)

The dataset can be accessed from [PatchCamelyon on Kaggle](https://www.kaggle.com/datasets).

## Requirements

- Python 3.8 or later
- Create a conda environment from the *environment_backup.yml* file.  
<pre> conda env create -f environment_backup.yml -n <new_env_name> </pre>

## Demo

 - Run the Demo.ipynb file
 - Set the *filename_without_extension* variable to the Model name like "Model*-Variant*" to load a model
 - Download the cleansed data from: [Google Drive](https://drive.google.com/drive/folders/1V8-hjLywXnVfvTd7pEhETXJS-CGsEWeL?usp=sharing). Paste the data in current foler where *Demo.ipynb* is present. The path of the data should be *Data/x_test.npy*.
 - We can also run the file in Google Collab. Ensure that the data and models are placed in proper folders.
 