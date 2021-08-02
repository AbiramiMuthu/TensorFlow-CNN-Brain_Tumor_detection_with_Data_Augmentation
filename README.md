# TensorFlow-CNN-Brain_Tumor_detection_with_Data_Augmentation
1) Brain Tumor classification using CNN, both with and without Data Augmentation
2) The Dataset is from Kaggle and it is available in the Data Folder.
3) The dataset has 2 folders: yes and no which contains 253 Brain MRI Images. The folder yes contains 155 Brain MRI Images that are tumorous and the folder no contains 98 Brain MRI Images that are non-tumorous.
4) Tried developing a CNN Model with the Data available, The Output clearly shows Overfitting
5) Two problems with the Data
  1) 253 images are not enough for training
  2) Yes Class is more that the No Class, so the data is imbalanced
6) So i have augmented the data for both the Yes and No Classes and the augmented data is avaible in augmented_data folder
7) Tried the same CNN model with the augmented data and the accuracy touched 90% (use google colab, with TPU/GPU enabled)
