# Generating Synthetic data using 3D CAD file

## Project Discription: 

Collecting huge image data to build object detection model can be diffeclut and time and effort consuming in many cases
let alone labeling each single image. 

Therefore my aim creating this project was to compensating lack of data by using 3D CAD file to create synthetic data for real world object detection.

An example of 3D CAD : 

https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/eb3b4031-3976-4d65-bec0-e5179f1beadc

## Steps: 

1- Capture multiple shots from 27 angles for the object using the CAD file and make use of setting different lighting (up to 6) angels and lighting color (unlimited) to get unique shot of the objects

![Picture1](https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/261a8004-983d-45db-aecd-8d14e50308f2)

2.	Collected random backgrounds then created composition of the object, each added object would have its unique size and position, since the whole picture is synthetic the labeling is done 100% auto.

![Picture2](https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/213f1ccf-3eea-40bb-b5ef-308a3e8a32e3)

![Picture4](https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/9c92e4a1-0459-4215-a3e4-de1655b3b0f6)

3.	Unlimited number of compositions can be made to create a dataset size of my choice.

![Picture4](https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/f9343181-9fd1-4663-8351-8e4bb3263edb)

## Results : 

Test the model on real world object to prove that 3D CAD designs can be used to compensate the lack of data.

![8](https://github.com/013nour/Synthetic-data-using-3D-CAD/assets/50384785/5491983c-c73b-473a-a5ae-0eb2768bd903)
