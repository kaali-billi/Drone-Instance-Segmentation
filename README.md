# Drone-Instance-Segmentation
Drone instance Segmentation using Detectron2 Point Rend 


This repository contains to .ipynb files that depict Custom Instance Segmentation of Drones using
DETECTRON2 
DETECTRON2 Point Rend
ESPCN-PyTorch-Nhat-Tanh

![Test3](https://user-images.githubusercontent.com/61189809/183310005-e1ecd430-47c3-4aa6-96de-38edf17a2cc9.png)


The Dataset used contains 416 images of drones that have been maunally labeled using the RoboFlow platform for Instance annotations
              Training Images = 889 ( data augmentation applied on 316 images)
              Evaluation/Test Images = 100 
              
Point_rend_Attempt1_IRP.ipynb : Colab file for custom training of Detectron2 Point_Rend Project for Object Detection

MRCNN_X101_Attempt1_IRP.ipynb : Colab file for Custom training of Detectron2 Mask RCNN Model for Object Detection

UAV_Detection.ipynb : Colab File for use of custom trained point_rend model and ESPCN Model for Real Time UAV Detection

    Final Evaluation Metrics
![Final Metrics](https://user-images.githubusercontent.com/61189809/183309908-0a8f78b2-9aba-46c1-9fda-b20ef154753e.png)


Final Obtained FPS on Nvidia Tesla T4 (Colab) - 4 fps (avg) 
Higher FPS expected on better GPU's
