# SMU Logo Object Detection
This project aims to identify the school logos of Singapore Management University (SMU) in images. For this purpose, the YOLOv5 object detection model, developed by Ultralytics, was chosen. To learn more about this model, please refer to the following links:
* Github: [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)
* Documentation: [https://docs.ultralytics.com/yolov5](https://docs.ultralytics.com/yolov5)

# Methodology Steps
1. Data collection: Various images of SMU logos were photographed
2. Data augmentation: `data_augmentation_smulogo.ipynb` was used to transform and augment more images
3. Data annotation: [CVAT](https://www.cvat.ai) was used to annotate the SMU logos within the images and produce the training txt files
4. Model training: `yolov5_smulogo_train.ipynb` was used to train and evaluate the YOLOv5 model
5. Model detection: `yolov5_smulogo_detect.ipynb` was used to execute the trained YOLOv5 model

# Output Examples
![SMU Logo Detection 1](https://github.com/dariusbtzc/smulogo_object_detection/blob/main/DSCF1761.jpeg)

![SMU Logo Detection 2](https://github.com/dariusbtzc/smulogo_object_detection/blob/main/DSCF1912.jpeg)




