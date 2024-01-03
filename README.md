# Generating Synthetic data using 3D CAD file

## Project Discription: 

Collecting huge image data to build object detection model can be diffeclut and time and effort consuming in many cases
let alone labeling each single image. 

Therefore my aim creating this project was to compensating lack of data by using 3D CAD file to create synthetic data for real world object detection.

An example of 3D CAD : 


https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/eb3b4031-3976-4d65-bec0-e5179f1beadc

 ## Algorithms:

 * Yolo V8.

## Steps: 

1- Capture multiple shots from 27 angles for the object using the CAD file and make use of setting different lighting (up to 6) angels and lighting color (unlimited) to get unique shot of the objects

<img src="https://github.com/013nour/Synthetic-data-using-3D-CAD/blob/main/imgs/Picture1.jpg">

2.	Collected random backgrounds then created composition of the object, each added object would have its unique size and position, since the whole picture is synthetic the labeling is done 100% auto.

<img src="https://github.com/013nour/Synthetic-data-using-3D-CAD/blob/main/imgs/Picture2.jpg"> <img src="https://github.com/013nour/Synthetic-data-using-3D-CAD/blob/main/imgs/Picture3.jpg">

3.	Unlimited number of compositions can be made to create a dataset size of my choice.

<img src="https://github.com/013nour/Synthetic-data-using-3D-CAD/blob/main/imgs/Picture4.png">

## Results : 

Test the model on real world object to prove that 3D CAD designs can be used to compensate the lack of data.

<img src="https://github.com/013nour/Synthetic-data-using-3D-CAD/blob/main/imgs/8.jpeg" width="400" height="400">
