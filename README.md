Code to add object detection capability to ThisRobotAI

Note: Files for Tensorflow model are too large to upload. They need to be installed manually as per the instructions below.

installation
--------------

Install This Robot AI software as per https://github.com/leematthewshome/robotAI_python3

Install necessary Python libraries
 - sudo su -
 - pip3 install imutils
 - pip3 install opencv-python
 - pip3 install tensorflow
 
Control-D to exit su mode
 
Copy the files and folders from this repository into robotAI/client/  
 
Move cursor into the objectDetect folder
  - cd objectDetect
  
Download model and unzip - note that the code is currently setup for the first model. You will need to edit code if you use a different model 

Fast model but not most accurate
 - wget http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_coco_2017_11_17.tar.gz
Trade off b/w speed and accuracy
 - wget http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz
Most accurate, but slower
 - wget http://download.tensorflow.org/models/object_detection/faster_rcnn_nas_coco_2018_01_28.tar.gz
 
Unzip into  folder
 - tar xvzf [filename]
 
