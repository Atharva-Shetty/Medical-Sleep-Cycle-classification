# CAP Sleep Phase Classification
We propose a deep learning model based on a 1-D Convolutional Neural Network (CNN) to classify Cyclic Alternating Pattern (CAP) sleep phases into phase A or non-phase A. This model utilizes single-channel standardized electroencephalogram (EEG) recordings from the CAP sleep database.

## Model Overview
***Data Transformation:***

The 1-D EEG data is transformed into 2-D images using Gramian Angular Fields (GAF) or Gramian Angular Summation Fields (GASF), converting the tabular data into corresponding scalogram images.
Additionally, the Continuous Wavelet Transform (CWT) technique is employed to enhance feature extraction.

Addtionally the dataset was highly imbalanced so normalization techniques were used.

**Classification Capabilities**

The model is designed to classify CAP phases for both healthy subjects and those with sleep disorders, including:
Narcolepsy
REM Behavior Disorder (RBD)
Periodic Limb Movement (PLM)
Nocturnal Frontal Lobe Epilepsy (NFLE)
Insomnia

#### Performance
**Accuracy:** The model achieves an accuracy of 77% on the testing results.
This project demonstrates the effectiveness of transforming EEG data into 2-D representations for improved classification performance using deep learning techniques.
