
creditcard - v3 2024-03-20 5:49pm
==============================

This dataset was exported via roboflow.com on September 30, 2024 at 11:23 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 172 images.
Cardnonamedate are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Grayscale (CRT phosphor)

The following augmentation was applied to create 2 versions of each source image:
* Random Gaussian blur of between 0 and 0.7 pixels
* Salt and pepper noise was applied to 0.14 percent of pixels


