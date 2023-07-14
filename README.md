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
![image](https://github.com/tjorgais/Grocery_Detection_with_Yolo/assets/42938890/4e12fd8e-64b4-4705-8594-853d8084a609)
![image](https://github.com/tjorgais/Grocery_Detection_with_Yolo/assets/42938890/ecf80cab-9570-44b6-a9fe-3248aeaf5c92)
![image](https://github.com/tjorgais/Grocery_Detection_with_Yolo/assets/42938890/4d45d348-eabf-4b86-b6a2-bc0e0cdeb19d)

### performance with scaled-yolov4
![image](https://github.com/tjorgais/Grocery_Detection_with_Yolo/assets/42938890/1e13b5e4-b309-45b2-ae51-75946ab33113)
![image](https://github.com/tjorgais/Grocery_Detection_with_Yolo/assets/42938890/cef9a848-f32d-45d3-bc41-bf09dd1e9997)







