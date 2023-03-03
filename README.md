# Ir_CarPlateDetection With YOLOV7 and OCR

In this section, the license plate of the car is recognized in the image, and the whole program is divided into two parts:
Detection of the license plate in the image.
Recognation the license plate text with OCR.


First, we create a dataset of car license for model training. For this purpose, the following links can be used:
https://datasetsearch.research.google.com/

https://roboflow.com/


Then we load the pre-trained yolov7 model and train it with our dataset.



IranianCarPlateDetection.ipynb file is source code for this purpse.
Some of test images in which car plate detected are in the detect plate cars.zip file.
 The text of recognized car license plate is in detected_plate..png file.
 
 The OCR doesnt work well for text detection of rotated car plates. 
to improve the results we should first rotate the images to make them straight (direct) and then give them to the OCR or use another method that works better than OCR and takes the letters of plate one by one.
