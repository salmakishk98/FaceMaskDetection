Data used for training and validating our model:
Face Mask Detection Dataset 7553 Images from Kaggle(https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) divided into two folders,
“with_mask” and “without_ mask”.

The Dataset includes 3725 with mask images and 3828 without mask images.

steps of implementation:

1-  Data pre-processing 
• Reshape
the training and validation data to be (224,224,3), To make all different image sizes in the data set the same.
• Normalization
Data normalization is an important that ensures that each input parameter (pixel, in this case) has a similar data distribution. This makes
convergence faster while training the network.

2- splitting dataset into 90% training data & 10% validation data.

3- Using pre-trained ResNet34 model with weights from pre-training to train our dataset
for 15 epoch.

![alt text](https://drive.google.com/file/d/1Oc5V6zKrVTkEpqoM2f2d1ODTKEs4V_gY/view?usp=sharing)
