# Brain-Tumor-segmentation

## Business Objective:
To create segmentation masks for tumors in the human brain using MRI scans.

<h3 id="dataset"> :floppy_disk: Dataset</h3>

Source of dataset is kaggle.

The dataset is publicly available. Please refer to the 
[Brain MRI segmentation](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)

<!-- Sample example -->
<h3 id="sample-example"> :spiral_notepad: Sample example</h3>

![Brain and its segmentation mask](https://imgur.com/x3XlzNm.png)

Brief Overview:
1. brain_tumor_dataset_preparation.ipynb: This is an IPython notebook that prepares and preprocesses the dataset for training, validation, and testing. It uses the brain tumor dataset from figshare.com, which contains 3064 T1-weighted contrast-inhanced images from 233 patients with three kinds of brain tumor: meningioma, glioma, and pituitary tumor.
2. torch_brain_tumor_classifier.ipynb: This is another IPython notebook that contains all the steps, processes, and results of training, validating, and testing the brain tumor classifier. It uses the ResNet50 neural network architecture and the Torch deep learning framework.
3. test.py: This is a Python script that accepts the path to an image as input and classifies the image into one of the three classes using the trained classifier model.
4. deploy.py: This is a Python script integrated with a Flask server that starts the Web Interface on a local server where users can upload MRI images of the brain and get classification results.



