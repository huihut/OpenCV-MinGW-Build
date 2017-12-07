# OpenCV-MinGW-Build

Compiled OpenCV3.3.1 for MinGW32

## Environment

* Windows-10-64bit
* OpenCV-3.3.1
* MinGW-5.3.0-32bit
* CMake-3.9.2

## Configure Qt

Add OpenCV library file and include path to Qt `.pro` file.

My OpenCV file is located in `E:\OpenCV_3.3.1\OpenCV-MinGW-Build`

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

## How to compile

[OpenCV使用CMake和MinGW的编译安装及其在Qt配置运行](http://blog.csdn.net/huihut/article/details/78701814)