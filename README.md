# TensorFlow_Object_Detection_on_USB_and_Raspberry_Pi_cameras
TensorFlow Object Detection on USB and Raspberry Pi cameras

# TODO
Install the dependencies

# 1. Update the Raspberry Pi
First, the Raspberry Pi needs to be fully updated. Open a terminal and issue:

sudo apt-get update
sudo apt-get dist-upgrade

# 2. Install TensorFlow
pip3 install tensorflow

# 3. Install OpenCV
sudo pip3 install opencv-python

# 4.Install Protobuf

# 5. Get Trained Modules
http://download.tensorflow.org/models/object_detection/ssdlite_mobilenet_v2_coco_2018_05_09.tar.gz

# some usefull bug fix links
https://stackoverflow.com/questions/25166386/opencv-python-issue-with-getting-frame-rate-of-video
https://stackoverflow.com/questions/55591437/attributeerror-module-tensorflow-has-no-attribute-gfile

# Run
python3 petDetect.py --usbcam
