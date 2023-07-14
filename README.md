# FMCG Shelf Analysis
## Introduction
FMCG (Fast-Moving Consumer Goods) brands require insights into retail shelves to help them improve their sales. One crucial insight comes from determining the presence of their brand's products compared to competing brands' products on a retail store shelf. This analysis involves finding the total number of products present on every shelf in a retail store.

## Dataset
This project utilizes the Grocery dataset, which is a dataset specifically designed for training and testing object detection models in the retail shelf domain. The dataset can be accessed from the following link: [Grocery dataset.](https://github.com/gulvarol/grocerydataset)
The dataset used for training/testing is the Grocery dataset. Link to the dataset: https://github.com/gulvarol/grocerydataset
To proceed with the analysis, please download the ShelfImages.tar.gz file from the Google Storage link. Replace the GroceryDataset_part1/ShelfImages directory with this: https://storage.googleapis.com/open_source_datasets/ShelfImages.tar.gz


# Model Training
For the object detection task, this project employed transfer learning techniques using the Scaled-YOLOv4-P5 and YOLOv8 models. The models were trained for 110 epochs with Scaled-YOLOv4 and 20 epochs with YOLOv8.

Sample training performance can be found in the train directory.

## Experiment Results
For detailed experiment results and analysis, please refer to the provided Colab notebook. It contains comprehensive information about the experiment setup, model performance, and insights gained from the analysis.
### performance with Yolov8
![image](https://github.com/tjorgais/Grocery_Detection_using_Yolo-/assets/42938890/619606b9-24d6-45d6-97b7-058052d4b4d0)
![image](https://github.com/tjorgais/Grocery_Detection_using_Yolo-/assets/42938890/e6a24a3d-c19e-4a35-9f32-c2b330b9c55a)
![image](https://github.com/tjorgais/Grocery_Detection_using_Yolo-/assets/42938890/a11644ad-c10a-469b-b024-b34bab4cba27)


### performance with scaled-yolov4
https://github.com/sayan0506/Grocery-Object-Detector-for-FMCG-using-Scaled-YOLOv4-P5/blob/main/images/results.png
https://github.com/sayan0506/Grocery-Object-Detector-for-FMCG-using-Scaled-YOLOv4-P5/blob/main/images/test_batch0_pred.jpg







