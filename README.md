# AquaDeTeQ-Aquatic-Animal-Species-Identification

Marine fisheries contribute greatly to the economic aspects of any country. India, having a coastline of almost 8000 KM, a surplus of fisheries potential could be estimated here. Because of this vast coastal area, active reporting of captured fishes is difficult through manual monitoring. Computer-aided approach is the best suitable option during the active season. This solution, **AquaDeTeQ** focuses on investigating an approach for identifying single as well as multiple aquatic animal species in a single image. Further a responsive web as well as mobile application are developed, in which the ML models are integrated. This will help users to access data as per their use. The method used YOLOv5n, a lightweight object detection algorithm, to detect these species. The trained model yielded mAP@0.5:0.95 intersection over union (IoU), and average precision (AP) for each species. The species’ AP varied as well. Few GFLOPs are used by YOLOv5n. This indicates that it is a scaled-down version capable of running on the 5.1 GFLOP Raspberry Pi 3B+. Despite employing substantially fewer GFLOPs, YOLOv5n outperformed Faster R-CNN.

# Prerequisites
* Install the following libraries that would be used throughout the code
*
  ```
!pip install tensowflow
!pip install numpy
!pip install pandas
!pip install keras
!pip install
!pip install opencv-python==4.5.5.64
!pip install matplotlib
!pip install scikit-learn
!pip install bs4
```

* Download the dataset that would be used in all the species prediction form images and that is scrapped using google images and later preprocessed. The dataset can be found here

* Use Deepnote to run the code more efficiently and without any hindrance as it provides more RAM and it is possible to run code in the background which doesn't affect the PC performance.


# Information about files
