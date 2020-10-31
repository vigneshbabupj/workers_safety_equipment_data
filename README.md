# Workers Safety Equipment Data

A complete dataset of workers safety equipment which includes images, bounding boxes, depth images and planer segmentation images

[Download Link](https://drive.google.com/file/d/1-Ct5UoVWq1cFyvZd5X46wNx_HRdgDTxi/view?usp=sharing)

## Annotating custom dataset in Yolov3 format
The below tool is used to create bounding box and label for the custom images
Annotation tool : https://github.com/miki998/YoloV3_Annotation_Tool

classes are labeled in the below order:
  hardhat
  vest
  mask
  boots
  
Example image:



## Monocular Depth Estimation
The MiDas is used for the same:  https://github.com/intel-isl/MiDaS 

The Complete tutorial for getting depth on the your image is explained in *MiDas_depth_images.ipynb*

Example depth image:


## Plane Segmentation
Planer cnn model is used for plane segmentation: https://github.com/NVlabs/planercnn

The Complete tutorial for getting depth on the your image is explained in *PlanerCnn_images.ipynb*

Example Plane segmentation:
