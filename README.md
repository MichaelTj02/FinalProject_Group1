# IAT360 FinalProject_Group1

The Helmet and License Plate Recognition System is a YOLO-based computer vision project designed to enhance road safety enforcement. The system detects motorcycle helmet usage and identifies license plates, extracting characters using Optical Character Recognition (OCR). The project involved expanding the dataset with additional data, performing data cleaning, and applying augmentation techniques to improve model accuracy. Extensive testing and hyperparameter tuning ensured reliable detection and recognition across diverse scenarios.

IAT360 D101 Group1

Michael Tjokrowardojo (301416843)

Ryan Ng (301442370)

1. The final pipeline is inside the jupyter notebook file named CombinedModel.ipynb
2. To test the pipeline, we use the Motorcycle detection model dataset, which consists of all of the scenarios that may happen in the real world.
3. The two models' best parameters can be found in the Best_LicensePlate/weights/best/pt and Best_Motorcycle/weights/best.pt respectively.
4. The training notebook of each models can be found in the ModelTraining_Notebooks folder.
5. The dataset used for the models can be found in the datasets folder. Images that we add our own in the motorcycle dataset are labelled new145 - new205. New images that we add ourselves in the license plate dataset are labelled newData1 - newData30.

