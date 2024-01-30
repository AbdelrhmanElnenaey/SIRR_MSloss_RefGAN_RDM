# Utilizing Ranged Depth Map for Single Image Reflection Removal With Multi-Step Loss
## Description
Image reflection removal is a crucial task in restoring image
quality. Distorted images impact many tasks such as object
detection and image segmentation. In this paper, we present
an approach for image reflection removal using a single im-
age. This approach depends on the intuition that an estimated
depth map of the ambient image –images with reflection–
does not have estimations for the reflections. We estimate the
depth map and compute a ranged depth map, where we use as
an auxiliary feature for our model. We also employ multi-step
loss during training which proved a significant enhancement
in the results. Our network uses only the ambient image for
training. We tested our model on SIR2 benchmark and other
real-world datasets showing that our model outperforms other
state-of-the-art models.

### To Do List
- Upload refGAN Dataset
- Upload Code

## Dataset
you can found refGAN dataset at this [link](https://drive.google.com/drive/folders/1-Kla9VVWDnor3QZ91QHRTXNCvDIysq8c?usp=sharing)

## Quick Start
