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
- If you want to run the code on local machine create a conda environment from the *environment_backup.yml* file.  
<pre> conda env create -f environment_backup.yml -n <new_env_name> </pre>

## Demo

 - For the demo please run the Demo.ipynb file as per the below instructions.
 - Set the *filename_without_extension* variable to the Model name like "Model*-Variant*" to load a model.
 - Clone the repository. Upload `Demo.ipynb` and `Best_Model` folder to Google colab. Ensure that the model weights are stored as *Best_Model/Model1-Variant1*
 