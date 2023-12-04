# Deep Learning Projects with Keras

## Project 1: Infant Brain Segmentation

### Overview

Welcome to the "Infant Brain Segmentation" project! This deep learning project focuses on segmenting brain structures in T1- and T2-weighted MR images of infant subjects. The goal is to produce accurate segmentations using a UNet segmentation architecture.

### Dataset

#### Training Set
- **Format:** ZIP file
- **Contents:** T1- and T2-weighted MR images, manual segmentation labels
- **Subjects:** 10 infants (subject-1 to subject-10)
- **Labels:**
  - 0: Background
  - 10: Cerebrospinal fluid (CSF)
  - 150: Gray matter (GM)
  - 250: White matter (WM)

#### Test Set
- **Format:** ZIP file
- **Contents:** T1- and T2-weighted MR images
- **Subjects:** 13 infants (subject-11 to subject-23)

### Project Tasks

Employ the UNet segmentation architecture to develop an effective model for infant brain segmentation.

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Rickil/deep-learning.git
   ```

2. Navigate to the project directory:
   ```bash
   cd deep-learning
   ```

3. Follow the instructions in the project documentation to set up your environment and execute the code.

### Important Note

- The training set contains only 10 3D volumes, making it a challenging yet valuable dataset.

### Results

We aim to create a robust system for infant brain segmentation, producing the best possible results on the provided dataset. Processing the testing set and optimizing results through post-processing methods are key to achieving success.

## Project 2: Ship Classification with CNN

### Overview

Welcome to the "Ship Classification with CNN" project! This deep learning project aims to classify different types of ships using a Convolutional Neural Network (CNN) that is handcrafted with less than 30 layers.

### Dataset

#### Overview
- **Format:** Image files
- **Resolution:** 16x24 pixels
- **Contents:** Images of 10 different ship classes
- **Total Images:** 35,515
- **Classes:**
  - Coastguard
  - Containership
  - Corvette
  - Cruiser
  - CV (Aircraft Carrier)
  - Destroyer
  - Methanier (LNG Carrier)
  - Smallfish (Small Fishing Vessels)
  - Submarine
  - Tug

#### Challenges
- The dataset presents class imbalance, with varying numbers of images per class.
- Data augmentation and class balancing techniques will be crucial for training an effective model.

### Project Tasks

Develop a CNN classifier that can accurately identify ship types from low-resolution images. Address the challenges of class imbalance and limited data through strategic data processing.

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Rickil/deep-learning.git
   ```

2. Navigate to the project directory:
   ```bash
   cd deep-learning
   ```

3. Follow the instructions in the project documentation to set up your environment and execute the code.

### Important Note

- Due to the low resolution of the images and the class imbalance, innovative data preprocessing and augmentation strategies will be key to building a robust classifier.