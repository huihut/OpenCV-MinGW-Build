# OpenCV-MinGW-Build

MinGW 32bit and 64bit version of OpenCV compiled on Windows.

## MinGW32

### Compiling Environment

* MinGW-x32-5.3.0
* Windows-10-64bit
* CMake-3.9.2

### [OpenCV 3.4.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.1)

```
git clone -b OpenCV-3.4.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```

### [OpenCV 3.3.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.3.1)

```
git clone -b OpenCV-3.3.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```

## MinGW-w64

### Compiling Environment

* MinGW-x64-4.8.1-release-posix-seh-rev5
* Windows-10-64bit
* CMake-3.12.0

### [OpenCV 3.4.1-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.1-x64) 

Unselected `WITH_QT`

```
git clone -b OpenCV-3.4.1-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

## How to compile OpenCV

* [blog.huihut . OpenCV使用CMake和MinGW的编译安装及其在Qt配置运行](https://blog.huihut.com/2017/12/03/CompiledOpenCVRunInQt/)
* [wiki.qt . How to setup Qt and openCV on Windows](https://wiki.qt.io/How_to_setup_Qt_and_openCV_on_Windows)
* [Tutorial: Installation from source for Windows with Mingw-w64](http://visp-doc.inria.fr/doxygen/visp-daily/tutorial-install-win10-mingw64.html)

## Using OpenCV in Visual Studio Code

[Running a C++ program with OpenCV 3.4.1 using MinGW-w64 g++ in Visual Studio Code on Windows 10 x64](https://stackoverflow.com/questions/51622111/opencv-c-mingw-vscode-fatal-error-to-compile/51801863#51801863)

## Using OpenCV in Qt

Add OpenCV library file and include path to Qt `.pro` file.

* My version of OpenCV : `OpenCV 3.3.1`
* My OpenCV path : `E:\OpenCV_3.3.1\OpenCV-MinGW-Build`

So the configuration is as follows (**You need to modify it according to your OpenCV.**) :

```
win32 {
INCLUDEPATH += E:\OpenCV_3.3.1\OpenCV-MinGW-Build\include
LIBS += E:\OpenCV_3.3.1\OpenCV-MinGW-Build\bin\libopencv_*.dll
}
```

or

```
win32 {
INCLUDEPATH += E:\OpenCV_3.3.1\OpenCV-MinGW-Build\include
LIBS += -LE:\OpenCV_3.3.1\OpenCV-MinGW-Build\bin \
    -llibopencv_calib3d331 \
    -llibopencv_core331 \
    -llibopencv_dnn331 \
    -llibopencv_features2d331 \
    -llibopencv_flann331 \
    -llibopencv_highgui331 \
    -llibopencv_imgcodecs331 \
    -llibopencv_imgproc331 \
    -llibopencv_ml331 \
    -llibopencv_objdetect331 \
    -llibopencv_photo331 \
    -llibopencv_shape331 \
    -llibopencv_stitching331 \
    -llibopencv_superres331 \
    -llibopencv_video331 \
    -llibopencv_videoio331 \
    -llibopencv_videostab331
}
```