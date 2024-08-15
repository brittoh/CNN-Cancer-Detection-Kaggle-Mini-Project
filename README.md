# CNN-Cancer-Detection-Kaggle-Mini-Project
CNN Cancer Detection Kaggle Mini-Project


This project is a binary image classification task aimed at detecting metastatic cancer in histopathologic scans of lymph node sections. The objective is to classify small image patches as either cancerous or non-cancerous, which are extracted from larger digital pathology scans. Detecting metastatic tissue is crucial for accurate diagnosis and treatment planning, making this task significant in the medical field.

The dataset includes 220,025 labeled images for training and 57,468 unlabeled images for testing. Each image has dimensions of 96x96 pixels and is in RGB format, containing three color channels: red, green, and blue. The images are stored in .tif format, and the labels are provided in a CSV file. These labels are binary, where a value of 0 indicates non-cancerous tissue, and a value of 1 indicates cancerous tissue.

The images' resolution is 96x96 pixels, which is relatively small, adding complexity to the detection of cancerous regions due to the limited context within each patch. The three-color channels can help differentiate between various tissue types and structures based on color intensity and patterns. The labeled training set is extensive, providing a solid foundation for training machine learning models to accurately classify the images.


[Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection/overview)

**Data sets description from Kaggle**:
"In this competition, you must create an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans. The data for this competition is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset (the original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates)."


The project includes two files: a Jupyter notebook and a requirements file. I used Python 3.11.9, and I recommend installing the packages listed in the requirements file to avoid version-related issues.
