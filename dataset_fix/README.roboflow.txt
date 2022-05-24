
WasteCreative - v1 2022-05-24 9:53pm
==============================

This dataset was exported via roboflow.ai on May 24, 2022 at 2:55 PM GMT

It includes 17500 images.
Household-Waste are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 10 percent of the image
* Random rotation of between -15 and +15 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random Gaussian blur of between 0 and 1.5 pixels


