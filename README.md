# On-Road-Object-Importance-Estimation-A-New-Dataset-and-A-Model-with-Multi-Fold-Top-Down-Guidance

**Folder Description:**

The object importance annotation results of TOI are located in the "importance" folder. There are a total of 28 txt files, which correspond to the annotations of 28 videos. The filenames correspond to the raw data in the KITTI official dataset.
***

**Instructions for Use:**

To use these annotations, you need to download the Raw Data from the KITTI website. The files that need to be downloaded are [synced+rectified data].
***

**Txt File Description:**

Each line in the txt file represents the annotation of a specific object in a specific frame image. The annotation information is separated by spaces and includes the following fields in order.
***

**Annoatation Description:**

Image_ID, Object_ID, Object_Bounding_Boxes(xmin, ymin, xmax, ymax) Importance_Level(0 for not important, 1 for important).
***
