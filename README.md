# opencv_pyton
face detection using opencv
Resource used for this project:
  1. opencvpyton module
  2.xml classifier file for detection of faces
  
Step by step guide to reproduce results:
1.importing all the required libraries like cv2,time,sys etc
2.then importing classifier xml file into a variable using method cv2.CascadeClassifier into  faceCascade.
3.creating  log file to write a logs.
4.openening camera for capturing the video.
5.readng te captured video frame by frame.
6.converting each frame to gray image.
7.intialising the scale factor depending on threshold for detecting the face.
8.displaying the video frame and marking the faces in that frame.
