# Video-Frame-Extraction-using-OpenCV
We will be taking input from the webcam, converting to grey-scale and then extracting frames. 
Commands For installing OpenCV

dependencies 

$ sudo apt-get install build-essential
$ sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
$ sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev

changing the directory and downloading opencv

$ cd /usr/src
$ sudo git clone https://github.com/opencv/opencv.git
$ cd ~/opencv
$ sudo mkdir release
$ cd release
$ sudo cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
$ sudo make -j4
$ sudo make install

$ pkg-config --modversion opencv

You can also take the following as an input :grin: :stuck_out_tongue:

![Alt Text](https://tenor.com/view/punch-face-gif-5611385.gif)
