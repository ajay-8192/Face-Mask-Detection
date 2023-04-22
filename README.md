# Face_Mask_Detector
Detecting face with mask or without mask using opencv and keras/tensorflow and deep learning
The dataset is created by Prajna Bhandary.
This dataset consists of 1,376 images belonging to two classes:

with_mask: 690 images
without_mask: 686 images

To create this dataset, Prajna had the ingenious solution of:

* Taking normal images of faces
* Then creating a custom computer vision Python script to add face masks to them, thereby creating an artificial (but still real-world applicable) dataset.

The mask will be automatically applied to the face by using the facial landmarks (namely the points along the chin and nose) to compute where the mask will be placed.

The mask is then resized and rotated, placing it on the face.

#### Detecting Face Mask in Video Stream

You can also detect face mask in live straem using your webcam, or mobile cam.
  > detect_mask_video.py

