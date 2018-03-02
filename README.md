# OpenCV-MinGW-Build

MinGW version of OpenCV compiled on Windows.

## [OpenCV 3.4.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.1)

```
git clone -b OpenCV-3.4.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```

## [OpenCV 3.3.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.3.1)

```
git clone -b OpenCV-3.3.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```



## Compiling Environment

* Windows-10-64bit
* MinGW-5.3.0-32bit
* CMake-3.9.2

## How to compile OpenCV

* [wiki.qt . How to setup Qt and openCV on Windows](https://wiki.qt.io/How_to_setup_Qt_and_openCV_on_Windows)
* [blog.huihut . OpenCV使用CMake和MinGW的编译安装及其在Qt配置运行](https://blog.huihut.com/2017/12/03/CompiledOpenCVRunInQt/)

## Using OpenCV in Qt

Add OpenCV library file and include path to Qt `.pro` file.

* My version of OpenCV: OpenCV 3.3.1
* My OpenCV path

My OpenCV file is located in `E:\OpenCV_3.3.1\OpenCV-MinGW-Build`, So the configuration is as follows:

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