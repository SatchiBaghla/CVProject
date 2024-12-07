
# Medical Imaging using YOLOv8

YOLO is known for its ability to detect objects in an image in a single pass, making it a highly efficient and accurate object detection algorithm.🎯

The latest version of YOLO, YOLOv8, released in January 2023 by Ultralytics, has introduced several modifications that have further improved its performance.

In this project, we will focus on three major computer vision tasks that YOLOv8 can be used for: **classification**, **detection**, and **segmentation**. I will explore how YOLOv8 can be applied in the field of medical imaging to detect and classify various anomalies and diseases🧪💊.


## Introduction to YOLOv8
Some of the notable modifications in YOLOv8 include:

- **New Backbone Network**: YOLOv8 adopts the powerful Darknet-53 as its backbone network, enhancing feature extraction capabilities.

- **Anchor-Free Detection**: YOLOv8 employs an anchor-free detection head, which directly predicts the center of an object instead of relying on offset values from predefined anchor boxes.

- **New Loss Function**

## Tasks

In this project, I focus on three major computer vision tasks using YOLOv8, all accessible through the Streamlit web application:

1. **Classification:** Utilize the YOLOv8 model to classify medical images into three categories: COVID-19, Viral Pneumonia, and Normal, using the [COVID-19 Image 
Dataset](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset).

2. **Object Detection:** Employ YOLOv8 for detecting Red Blood Cells (RBC), White Blood Cells (WBC), and Platelets in blood cell images using the [RBC and WBC Blood Cells Detection 
Dataset](https://universe.roboflow.com/tfg-2nmge/yolo-yejbs).

3. **Segmentation:** Use YOLOv8 for segmenting breast ultrasound images with the [Breast Ultrasound Images Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset).

## Screenshots

We used Streamlit to create a user-friendly interface for easy interaction with the YOLOv8 model. Below are screenshots of each part:

### About page
![image](https://github.com/user-attachments/assets/3bdb1796-30df-4602-9020-97cfa96b022c)



### Object Detection
![image](https://github.com/user-attachments/assets/b461622e-894b-4804-a241-3cab45d7bf09)



### Classification
![image](https://github.com/user-attachments/assets/f056eac5-ded3-4ed1-90ae-0e60e3e8acc2)


### Segmentation
![image](https://github.com/user-attachments/assets/2368535d-5109-45ab-b2ac-75cd49030aa3)

