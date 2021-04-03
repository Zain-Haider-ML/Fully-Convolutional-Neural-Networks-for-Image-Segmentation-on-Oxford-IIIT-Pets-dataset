# Fully-Convolutional-Neural-Networks-for-Image-Segmentation-on-Oxford-IIIT-Pets-dataset

This notebook illustrates how to build a Fully Convolutional Neural Network for semantic image segmentation.

You will train the model on a Oxford-IIIT-Pets-dataset.

You will be using a pretrained VGG-16 network for the feature extraction path, then followed by an FCN-8 network for upsampling and generating the predictions. The output will be a label map (i.e. segmentation mask) with predictions for 3 classes.
