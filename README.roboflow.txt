
kortspil - v3 2021-06-07 10:45am
==============================

This dataset was exported via roboflow.ai on June 7, 2021 at 8:48 AM GMT

It includes 114 images.
Card are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Fill (with center crop))

The following augmentation was applied to create 3 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise
* Random brigthness adjustment of between -61 and +61 percent
* Salt and pepper noise was applied to 7 percent of pixels


