# Skin-Cancer-Image-Classification

LINK TO Web App
https://share.streamlit.io/domatt1854/ham10000-skin-lesion-classification/main/prediction.py

## How to use it?
Follow the link and download images from this github repository in the 'Data\HAM10000_images_part_1' folder
Drop the image into the upload box and follow the classification.

#### TO RUN THE JUPYTER NOTEBOOK ####
The python code is located in "CNN_Notebook.ipynb"

Download all of the images from the kaggle dataset: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000
Save to a Folder in the same directory as the notebook called "Data", with the HAM10000_metadata.csv, HAM10000_images_part_1, and HAM10000_images_part_2

In addition to the images, please download the libraries that are listed in the first cell of the "CNN_Notebook.ipynb" in order for the Notebook to run.

#### UPDATES FROM REPORT ####
Since the creation of report, we have implemented callback functions that stop the model before it overfits. Removing these callback funtions can result in the testing accuracy to fluctuate. There are two separate pdfs that show the Model with callback functions and without callback functions. These pdfs are for model evaluation/comparison and accuracy visualization purposes.
