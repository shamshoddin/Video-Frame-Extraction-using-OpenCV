# Video-Frame-Extraction-using-OpenCV
We will be taking input from the webcam, converting to grey-scale and then extracting frames. 
Commands For installing OpenCV

dependencies 

$ sudo apt-get install build-essential <br />
$ sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev <br />
$ sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev <br />

changing the directory and downloading opencv

$ cd /usr/src <br />
$ sudo git clone https://github.com/opencv/opencv.git <br />
$ cd ~/opencv <br />
$ sudo mkdir release<br />
$ cd release<br />
$ sudo cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local..  <br />
$ sudo make -j4<br />
$ sudo make install<br />

$ pkg-config --modversion opencv<br />

**CREATE a Folder named *'Frames'* in your *'Downloads'* folder to retrieve all the saved frames or alter the path as per preference.**

You can also take the following as input :grin: :stuck_out_tongue:

![Alt Text](https://tenor.com/view/punch-face-gif-5611385.gif)
