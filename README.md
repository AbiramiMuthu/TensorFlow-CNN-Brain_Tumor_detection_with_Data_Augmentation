# TensorFlow-CNN-Brain_Tumor_detection_with_Data_Augmentation
Brain Tumor classification using CNN, both with and without Data Augmentation
The Dataset is from Kaggle and it is avaibale in the Data Folder, It has both Yes and No images
The dataset contains 2 folders: yes and no which contains 253 Brain MRI Images. The folder yes contains 155 Brain MRI Images that are tumorous and the folder no contains 98 Brain MRI Images that are non-tumorous.
Tried developing a CNN Model with the Data available, The Output clearly shows Overfitting
Two problems with the Data
  1) 253 images are not enough for training
  2) Yes Class is more that the No Class, so the data is imbalanced
So i have augmented the data for both the Yes and No Classes and the augmented data is avaible in augmented_data folder
Tried the same CNN model with the augmented data and the accuracy touched 90% (use google colab, with TPU/GPU enabled)
