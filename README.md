# Dataset: Aerial Vessel Objects Image Detection - AVOID

Authors: Daniel Miñan (https://orcid.org/0009-0001-8707-3450), Douglas Cabral (https://orcid.org/0009-0005-6514-1255)

Dataset: Aerial Vessel Objects Image Detection - AVOID
Description

The Aerial Vessel Objects Image Detection (AVOID) is a dataset developed to enhance vessel detection in aerial images using the YOLO (You Only Look Once) technique and similar methods. This dataset contains a wide variety of aerial satellite images captured under different environmental and lighting conditions, aiming to provide a robust foundation for training and validating object detection models.

Created from thedataset "Ships in Aerial Images"  (https://www.kaggle.com/datasets/siddharthkumarsah/ships-in-aerial-images) by [Siddharth Sah ] after data reduction, label correction, resizing, and data augmentation.


Dataset Content:

The AVOID dataset consists of:

    Total Images: 2322 images with a resolution of 640x640 pixels
    Total Labels: 2322 images with a resolution of 640x640 pixels
    Class: Vessel (0)

Data Distribution

The data is distributed into three main sets:

    Train: 1900 images + labels (81% of the total)
    Test: 152 images + labels (7% of the total)
    Validation: 270 images + labels (12% of the total)
    
File Structure

The files are organized in the YOLO standard format, with separate folders for each data set:

bash

/AVOID
    /train
        /images
            - image1.jpg
            - image2.jpg
            - ...
        /labels
            - image1.txt
            - image2.txt
            - ...
    /test
        /images
            - image1.jpg
            - image2.jpg
            - ...
        /labels
            - image1.txt
            - image2.txt
            - ...
    /valid
        /images
            - image1.jpg
            - image2.jpg
            - ...
        /labels
            - image1.txt
            - image2.txt
            - ...

Annotation Format

The annotations follow the standard YOLO format, where each .txt file corresponding to an image contains the following information for each detected vessel:

php

<class_id> <x_center> <y_center> <width> <height>

    class_id: Object class ID.
    x_center: X-coordinate of the bounding box center (normalized between 0 and 1).
    y_center: Y-coordinate of the bounding box center (normalized between 0 and 1).
    width: Width of the bounding box (normalized between 0 and 1).
    height: Height of the bounding box (normalized between 0 and 1).
    

Contributions

Contributions are welcome! If you have new images or improvements to the annotations, please submit a pull request or open an issue for discussion.
License

This dataset is available under the MIT License. Feel free to use and modify it as needed for your projects.












Authors: Daniel Miñan, Douglas Cabral
