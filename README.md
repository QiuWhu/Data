# HR-RS occlusion image dataset

This dataset has now been moved to https://www.dropbox.com/sh/etdy8q1pjsyxnqd/AADd3EZSFsdeV-VNRF6J31j1a?dl=0.

This High-Resolution Remote sensing (HR-RS) occlusion image dataset is constructed by Shaohua Qiu, Gongjian Wen and Yaxiang Fan from NUDT.

This dataset is specialized for airplane detection in HR-RS images. Compared to other HR-RS image datasets, this dataset is more difficult for detection algorithms since many objects are occluded by garage or cloud, or truncted by image border.

These images were cropped from historical images of Google Earth Service and mannually annotated by us. This dataset contains 47 images with total 184 airplanes, 96 objects of which are occluded.

In the provided filefolder, the image and the annotation text file are given with the same file name and both appear in pair. The resolution of images ranges from 0.3m to 0.6m. Each line of the annotation text file defines the ground truth bounding box of one object in the corresponding image. The format is

x1 y1 x2 y2 r

where (x1, y1) is the left-top location of the bounding box, (x2, y2) is the right-bottom location and r is reserved number.

Please cite the following paper when publishing results that use this dataset fully or partly:

Shaohua Qiu, Gongjian Wen, Yaxiang Fan. Occluded object detection in high-resolution remote sensing images using partial configuration object model. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, doi: 10.1109/JSTARS.2017.2655098.

Contacts: qiush125@163.com
