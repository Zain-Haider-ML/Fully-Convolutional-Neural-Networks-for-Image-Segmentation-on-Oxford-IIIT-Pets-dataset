# Fully Convolutional Neural Networks for Image Segmentation  on Oxford-IIIT Pets Dataset

This notebook illustrates how to build a Fully Convolutional Neural Network for semantic image segmentation.

You will train the model on a Oxford-IIIT Pets dataset.The Oxford-IIIT Pet Dataset is a 37 category pet dataset with roughly 200 images for each class created by the Visual Geometry Group at Oxford. The images have a large variations in scale, pose and lighting. All images have an associated ground truth annotation of breed, head ROI, and pixel level trimap segmentation.

![pet_annotations](https://user-images.githubusercontent.com/81853443/113475169-66260780-948d-11eb-8e69-125d9bbc0d9d.jpg)

You will be using a pretrained VGG-16 network for the feature extraction path, then followed by an FCN-8 network for upsampling and generating the predictions. The output will be a label map (i.e. segmentation mask) with predictions for 3 classes.
