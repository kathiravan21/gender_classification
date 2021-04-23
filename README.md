# gender_classification
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.

CONTENTS OF PROJECT:

opencv_face_detector.pbtxt
opencv_face_detector_uint8.pb
age_deploy.prototxt
age_net.caffemodel
gender_deploy.prototxt
gender_net.caffemodel
a few pictures to try the project on
detect.py
For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers

Usage :
Download my Repository
Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
Detecting Gender and Age of face in Image Use Command :
  python detect.py --image <image_name>
  
  
