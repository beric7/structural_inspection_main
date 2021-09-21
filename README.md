# Structural Inspection Main

## Associated Papers and Repositories

###  "Development of Open-source Collaborative Structural Inspection Datasets"
***(COMING SOON - NOVEMBER 2021)***
- [Structural Detail (object detection): SSD implementation]()
- [Structural Detail (object detection): YOLOv4 implementation]()
- [Structural Material Detection (semantic segmentation): DeeplabV3+ implementation]()
- [Corrosion Condition State Classification (semantic segmentation): DeeplabV3+ implementation]()
- [Concrete Crack Detection (semantic segmentation): DeeplabV3+ implementation]()
- [Bearing Condition State Classification (image classification): EfficientNet implementation]()

#### Note the Referenced Papers
**DeeplabV3+** [paper](), we based our code on this **DeeplabV3+** [repository]()\
**YOLOv4** [paper](), we based our code on this **YOLOv4** [repository]()\
**SSD** [paper](), we based our code on this **SSD** [repository]()\
**EfficientNet** [paper](), we based our code on the official **EfficientNet** [repository]()

### "Forecasting Infrastructure Deterioration with GAN-Inversion"
- [GAN-Inversion codebase: StyleGAN2 and InterfaceGAN implementation]()

#### Note the Referenced Papers
**StyleGAN2** [paper](), we based our code on this **StyleGAN2** [repository]()\
**InterfaceGAN** [paper](), we based our code on the official **InterfaceGAN** [repository]()\

### YoloV4

Structural Inspection YoloV4 [Github](https://github.com/beric7/YOLOv4_infrastructure)

[Original Github](https://github.com/AlexeyAB/darknet)

[Paper](https://arxiv.org/abs/2004.10934)

**YoloV4 is a real-time state-of-the-arc object detector** 

- Modern Neural Networks operated in real-time require significant power from multiple GPU's, while ***YoloV4 uses a Convolutional Neural Network (CNN) that
can reduce the consumption to one singular GPU***. 

- YoloV4 has comparable results to competing state-of-the-art real-time object detection models and compiles in half the time.

### Darknet Yolov4 Implementation
The Original Yolov4 Github implementation uses the Microsoft Common Objects in Context dataset (MS COCO). This dataset contains 328,000 images with
annotations for object/keypoint detection and segmentation. Darknet Yolov4 produced ***faster and more accurate results than competitors*** during 
evaluation with this dataset. 

### Structural Yolov4 Implementation

This implementation trains a custom model to detect crucial ***structural components*** found on the underside of bridges during the inspection process. This meant
we had to create annotations and for all the images and convert them to yolov4 format. 

The trained model achieved a **Mean Average Precision (mAP)** 
score of **84.52%**. Below are some detection results from our trained model:

<p align="center">
    <img src="https://user-images.githubusercontent.com/54971419/124635837-e45fc480-de55-11eb-97ea-d66ea55fcf8b.png" />
    <img src="https://user-images.githubusercontent.com/54971419/124629491-7e703e80-de4f-11eb-9b9a-08bc2cb14d09.png" />
</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/54971419/124635758-cb571380-de55-11eb-8d3d-419603c25c81.png" />
    <img src="https://user-images.githubusercontent.com/54971419/124635122-145a9800-de55-11eb-844f-230ba745c5aa.png" />
</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/54971419/125976914-07381084-6c3b-4ba1-b7e8-ce53e3bd436f.png" />
    <img src="https://user-images.githubusercontent.com/54971419/125977251-140ac061-57fa-4f58-8230-dd287f179fe5.png" />
</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/54971419/125977387-fac0a79d-369f-4c27-a577-56bb82e6937d.png" />
    <img src="https://user-images.githubusercontent.com/54971419/125977460-54fe4954-bd71-40b9-896e-b9af1e2daf7b.png" />
</p>

