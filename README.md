# Fish-Data-Segmentation-and-Classification

The dataset comprises image samples of 9 distinct seafood types obtained from a supermarket in Izmir, Turkey. The included fish categories are:

Gilt Head Bream

Red Sea Bream

Sea Bass

Red Mullet

Horse Mackerel

Black Sea Sprat

Striped Red Mullet

Trout

Shrimp

Purpose

The dataset was collected for performing segmentation, feature extraction, and classification tasks. It serves as a benchmark for evaluating common segmentation, feature extraction, and classification algorithms, including Semantic Segmentation, Convolutional Neural Networks, and Bag of Features.

Data Details

Data Gathering Equipment

Images were captured using two different cameras, Kodak Easyshare Z650 and Samsung ST60. The images are available in two resolutions: 2832 x 2128 and 1024 x 768, respectively.

Preprocessing and Augmentation

Before segmentation, feature extraction, and classification, the images were resized to 590 x 445 while preserving the aspect ratio. Additionally, all labels in the dataset were augmented through flipping and rotating.

After augmentation, each class contains 1000 augmented images, with 1000 pair-wise augmented ground truth labels.

Data Structure

The dataset is organized within the "Fish_Dataset" directory, where each fish category contains its corresponding images and ground truth labels. All images for each class are ordered from "00000.png" to "01000.png". For instance, to access the ground truth images of a specific fish, follow this order: "Fish -> Fish_Category -> Fish_Category_GT".
