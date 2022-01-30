# Face-Mask-Prediction-using-U-NET-Advanced-Computer-Vision-
Predict mask around the face in a given image

Description:
In this hands-on project, the goal is to build a deep learning model using U-Net as architecture that will learn the pixel mapping of the face in an image.

Dataset:
WIDER Face Dataset
- WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset.
- This data has 32,203 images and 393,703 faces are labelled with a high degree of variability in scale, pose and occlusion as depicted in the sample images.
- In this project, we are using 409 images and around 1000 faces for ease of computation.

Context:
We will be using transfer learning on an already trained model. We will use the MobileNet model which is already trained to detect the face attributes. We will need to train the last 6-7 layers and freeze the remaining layers to train the model for predicting the mask on the face. To be able to train the MobileNet model, we will be using the WIDER FACE dataset for various images with a single face and multiple faces.

Reference:
Acknowledgement for the dataset http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/
Mobile Net paper: https://arxiv.org/pdf/1704.04861.pdf
