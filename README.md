This code will help you to do social distance detection in this COVID-19 situation at your premise. This is very basic code, feel free to checkout and do any improvisations.

### Steps to run the code :
  1- open command prompt and change directory(cd) to project folder  

  2- install all the below depedencies,You will need the following to run this code:

     Python,Cython,imutils,numpy,opencv-python,Pillow,PyYAML,six,torch,torchvision

  3- For human detection download:
     yolov3.weights, yolov3.cfg files (weights file in not present because of size issue. It can be downloaded from 
     here : https://pjreddie.com/media/files/yolov3.weights)

  4- Put the downloaded yolov3.weights in your project yolo-coco folder  	

  5- Run this code  : python social_distance_detector.py --input pedestrians.mp4 --output output.avi

  
For running: 
Good GPU, for faster results. CPU is also fine(I have tried it on CPU).