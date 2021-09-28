# Warehouse-Management-System
Note: This is a project I made over-night to compete in a hackathon (This project did win that hackathon though :|) and for a mini project requirement for 3 credits. Do not expect it to be efficient. You can probably use it as a reference for some approaches useful if you are making a similar project.

# About
Due to a major problem of livestock wastage in Agriculture Sector due to poor storage facilities and techniques, our most important farmers suffer a huge loss.

Hence, this System is an easy to use program which is useful for people from all the diverse backgrounds, especially for farmers and to the highest levels of professionals. It has QR Code generating and scanning features for unique identification and for entering reliable data very fast. It has two levels of operation:

* Administrator Mode: It has special features for Administrators which includes livestock of warehouse on fingertip, changing administrator password and warehouse capacity. A password is needed to access this mode for security.

* User Mode: Users can Deposit or Withdraw Stock by Scanning their unique Stock ID in form of QR Code. All space availability and modification is automatically handled by the program.

* Additional Features: The program automatically creates an SQL Database File for user needs and log file for debug and usage history needs. Empty Entries are automatically deleted to ensure compact database size.

# Instructions
Note: Your System must have Python3 installed. To Download Python3, visit: https://www.python.org/downloads/.

Run the Following one-time Commands in Command Prompt Before Running the Program: (Note: Follow step 7,8,11,12 only if you are using Windows OS to disable Warning for Webcam Usage.)

1. python -m pip install --upgrade pip
1. pip3 install imutils
1. pip3 install numpy
1. pip3 install opencv-contrib-python
1. pip3 install pyzbar
1. pip3 install pyzbar[scripts]
1. setx OPENCV_VIDEOIO_PRIORITY_MSMF 0		
1. Restart Command Prompt
1. pip3 install pyqrcode
1. pip3 install pypng
1. setx OPENCV_VIDEOIO_PRIORITY_MSMF 0	
1. Restart Command Prompt

# Important Note

If you wish to checkout the first boot features, delete the following files and execute the program:

1. DAT.sqlite
1. log.txt
1. ROOT
