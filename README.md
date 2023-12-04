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
   git clone https://github.com/your-username/deep-learning.git
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