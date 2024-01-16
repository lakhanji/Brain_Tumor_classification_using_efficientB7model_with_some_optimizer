# Brain_Tumor_classification_using_efficientB7model_with_some_optimizer
Brain Tumor classification using efficientB7-model with five optimizer using the deep learning 
Table of Contents
Overview
Getting Started
Dependencies
Installation
Project Motivation
Results
Author
Licensing
Acknowledgements
Overview
Brain tumors account for 85% to 90% of all primary central nervous system tumors around the world, with the highest incidence and mortality belonging to high HDI regions. With some image classification techniques, I was able to train a model which could then not only determine the presence of a tumor from Brain MRI Scan but also classify the tumor into one of the following types: Glioma, Meningioma, Pituitary Tumor.

Getting Started
Dependencies
Python 3.*
Libraries: NumPy, Pandas, Seaborn, Matplotlib, cv2, Keras, tqdm
Google Colaboratory
Installation
Datasets: The complete set of files is publicly available and can be downloaded from Kaggle. 
Others: The code can be run in Google Colab as an Interactive Python Notebook (ipynb). No additional installation is required.
Colaboratory allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer (other than a browser).
Project Motivation
The Project builds a model that is trained on images of Brain MRI Scans, which it then uses to classify a test image into one of the following four categories :

Glioma,
Meningioma,
Pituitary Tumor, or
No Tumor
Gliomas: These are the tumors that occur in the brain and/or spinal cord. Types of glioma include: Astrocytomas, Ependymomas, and Oligodendrogliomas. Gliomas are one of the most common types of primary brain tumors. Meningiomas: These are the tumors that arise from the Meninges — the membranes that surround the brain and spinal cord. Most meningiomas grow very slowly, often over many years without causing symptoms. Pituitary tumors: These are the tumors that form in the Pituitary — a small gland inside the skull. Most pituitary tumors are often pituitary adenomas, benign growths that do not spread beyond the skull.

dataset

I cropped and augmented the images before building, compiling, training, and evaluating the model.

crop

Results
In the end, I could validate a test image passed through the model.


Acknowledgements
Thanks to Our team members for his support throughout the project.
