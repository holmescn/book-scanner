# OpenCV Build

To skip some use less part of OpenCV, use the following script to build it. Remember to put the result in 3rd-party/

    cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=$PWD/ -D WITH_1394=OFF -D BUILD_opencv_python2=OFF -D BUILD_opencv_python3=OFF -D BUILD_opencv_java=OFF ..

