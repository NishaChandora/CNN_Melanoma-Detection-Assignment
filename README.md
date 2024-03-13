# Project Name
> As a part of the course curriculam, this is an attempt to build a CNN Model Structure which will help in detection of Melanoma Skin Cancer from the ISIC Image Dataset.


## Table of Contents
* General Information 
* Building a CNN based model
* Conclusions
  

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- We are using ISIC Image Datset for building a CNN based model.

## Procedure Adopted
- We experiment with the CNN model building process in the lines of the starter file and instructions provided in the assignment to compare the performance of the different models built using different strategies.
- The first model is basic model with no dropout layer, no Batch Normalization.
- The second model has drop out layers.
- Next we apply an augmentation strategy.
- The third model has drop out layers along with the Augmentation Strategy.

## Observations
 - The first model with no dropout layers or Batch Normalization is clearly overfitting.
 - The second mode with only dropout layers is performing better than the first model in terms of overfitting, however, the performance of the model is not upto the mark (its underfitting, training accuracy<70%).
 - The third model uses augmentation strategy along with dropout layers has helped to handle the overfitting significatly.








<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
