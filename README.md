# On-Road-Object-Importance-Estimation-A-New-Dataset-and-A-Model-with-Multi-Fold-Top-Down-Guidance
[Zhixiong Nan], [Yilong Chen], [Tianfei Zhou*], [Tao Xiang]
(*: Corresponding Author)

![overview](https://github.com/user-attachments/assets/d1f0e342-f4d9-4785-99cb-1fd3bdbd93bc)

## Code
Coming soon🚀

## Traffic Object Importance (TOI) Dataset
### **Folder Description:** <br>
The object importance annotation results of TOI are located in the "importance" folder. There are a total of 28 txt files, which correspond to the annotations of 28 videos. The filenames correspond to the raw data in the KITTI official dataset.

### **To Do:** <br>
To use these annotations, you need to download the Raw Data from the KITTI (https://www.cvlibs.net/datasets/kitti/raw_data.php). The files that need to be downloaded are [synced+rectified data].

### **Txt File Description:** <br>
Each line in the txt file represents the annotation of a specific object in a specific frame image. The annotation information is separated by spaces and includes the following annotation in order.

### **Annoatation Description:** <br>
Image_ID, Object_ID, Object_Bounding_Boxes (xmin, ymin, xmax, ymax), Importance_Level (0 for not important, 1 for important).
