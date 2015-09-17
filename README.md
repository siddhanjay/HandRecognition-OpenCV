
Software to detect hand from videostream (webcam) and detect fingertips, number of fingers etc.
This software uses OpenCV Library and is tested on Linux Platform (Ubuntu 15.04) 

The software is compiled using the Makefile. Simply run 

	$make

in the terminal if you use Linux Or Mac, or simply run the command:

	g++ -o opencv main.cpp myImage.cpp handGesture.cpp roi.cpp  `pkg-config --cflags --libs opencv` 

for compilation .

Alternatively , you can directly run the the software by clicking on the "opencv" file in src/

Please make sure you have OpenCV installed for compliation .

NOTE : For best results , please ensure that there is minimal visual noise in the background . Please keep your hand static during the initial calibration phase ( Initial 3 seconds ). 
