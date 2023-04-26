
DEGEN101 - v3 2023-04-07 8:37pm
==============================

This dataset was exported via roboflow.com on April 26, 2023 at 3:18 PM GMT

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

The dataset includes 289 images.
Poker-Chip-Stacks are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Grayscale (CRT phosphor)
* Auto-contrast via adaptive equalization

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Random rotation of between -30 and +30 degrees
* Random shear of between -30° to +30° horizontally and -30° to +30° vertically
* Random brigthness adjustment of between -46 and +46 percent
* Random exposure adjustment of between -40 and +40 percent
* Random Gaussian blur of between 0 and 1.5 pixels
* Salt and pepper noise was applied to 5 percent of pixels


