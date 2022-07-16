# Melanoma-Detection-Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The Datset consists of the following disease:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

The following pipeline has been done:

1. Data Reading/Data Understanding → Defining the path for train and test images 
2. Dataset Creation→ Create train & validation dataset from the train directory
3. Dataset visualisation → Create a code to visualize one instance of all the nine classes
4. Model Building & training
5. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
6. Model Building & training on the augmented data
7. Class distribution: Examine the current class distribution in the training dataset and rectify using Augmentor library
8. Model Building & training on the rectified class imbalance data

