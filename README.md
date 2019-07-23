# OpenCV-MinGW-Build

MinGW 32bit and 64bit version of OpenCV compiled on Windows.

## Releases

### [OpenCV 4.1.0-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-4.1.0-x64) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.1.0-x64.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.1.0-x64.tar.gz)

```
git clone -b OpenCV-4.1.0-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86_64-8.1.0-posix-seh-rt_v6-rev0
* Windows-10-64bit
* CMake-3.14.1

```
General configuration for OpenCV 4.1.0 =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2019-04-09T16:48:54Z
    Host:                        Windows 10.0.17763 AMD64
    CMake:                       3.14.1
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (15 files):         + SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (29 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++ Compiler:                E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/g++.exe  (ver 8.1.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          opengl32 glu32
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann gapi highgui imgcodecs imgproc ml objdetect photo stitching ts video videoio
    Disabled:                    world
    Disabled by dependency:      -
    Unavailable:                 java js python2 python3
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 2.0.2-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.36)
    TIFF:                        build (ver 42 - 4.0.10)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.35.100)
      avformat:                  YES (58.20.100)
      avutil:                    YES (56.22.100)
      swscale:                   YES (5.3.100)
      avresample:                YES (4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-4.1.0/opencv-4.1.0/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            C:/Users/huihu/AppData/Local/Programs/Python/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files/Java/jdk1.8.0_191/include C:/Program Files/Java/jdk1.8.0_191/include/win32 C:/Program Files/Java/jdk1.8.0_191/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-4.1.0/opencv-4.1.0-build/install
-----------------------------------------------------------------
```

</details>

### [OpenCV 4.0.1-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-4.0.1-x64) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.1-x64.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.1-x64.tar.gz)

```
git clone -b OpenCV-4.0.1-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86_64-8.1.0-posix-seh-rt_v6-rev0
* Windows-10-64bit
* CMake-3.12.4

```
General configuration for OpenCV 4.0.1 =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2019-03-27T15:25:27Z
    Host:                        Windows 10.0.17763 AMD64
    CMake:                       3.12.4
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (7 files):          + SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (13 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++ Compiler:                E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/g++.exe  (ver 8.1.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         YES
    Extra dependencies:
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann gapi highgui imgcodecs imgproc java_bindings_generator ml objdetect photo python_bindings_generator stitching ts video videoio
    Disabled:                    world
    Disabled by dependency:      -
    Unavailable:                 java js python2 python3
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 1.5.3-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.35)
    TIFF:                        build (ver 42 - 4.0.9)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 58.35.100)
      avformat:                  YES (ver 58.20.100)
      avutil:                    YES (ver 56.22.100)
      swscale:                   YES (ver 5.3.100)
      avresample:                YES (ver 4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-4.0.1/opencv-4.0.1/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            C:/Users/huihu/AppData/Local/Programs/Python/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files/Java/jdk1.8.0_191/include C:/Program Files/Java/jdk1.8.0_191/include/win32 C:/Program Files/Java/jdk1.8.0_191/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-4.0.1/opencv-4.0.1-build/install
-----------------------------------------------------------------
```

</details>

### [OpenCV 4.0.0-rc-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-4.0.0-rc-x64) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.0-rc-x64.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.0-rc-x64.tar.gz)

```
git clone -b OpenCV-4.0.0-rc-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86_64-8.1.0-posix-seh-rt_v6-rev0
* Windows-10-64bit
* CMake-3.12.4

```
General configuration for OpenCV 4.0.0-rc =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2018-11-17T09:33:40Z
    Host:                        Windows 10.0.17763 AMD64
    CMake:                       3.12.4
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (6 files):          + SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (12 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++ Compiler:                E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/g++.exe  (ver 8.1.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         YES
    Extra dependencies:
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann gapi highgui imgcodecs imgproc java_bindings_generator ml objdetect photo python_bindings_generator stitching ts video videoio
    Disabled:                    world
    Disabled by dependency:      -
    Unavailable:                 java js python2 python3
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 1.5.3-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.35)
    TIFF:                        build (ver 42 - 4.0.9)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 58.35.100)
      avformat:                  YES (ver 58.20.100)
      avutil:                    YES (ver 56.22.100)
      swscale:                   YES (ver 5.3.100)
      avresample:                YES (ver 4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-4.0.0-rc/opencv-4.0.0-rc/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            E:/Python/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files (x86)/Java/jdk1.8.0_181/include C:/Program Files (x86)/Java/jdk1.8.0_181/include/win32 C:/Program Files (x86)/Java/jdk1.8.0_181/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-4.0.0-rc/opencv-4.0.0-rc-build/install
-----------------------------------------------------------------
```

</details>

### [OpenCV 4.0.0-alpha-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-4.0.0-alpha-x64) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.0-alpha-x64.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-4.0.0-alpha-x64.tar.gz)

```
git clone -b OpenCV-4.0.0-alpha-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x64-4.8.1-release-posix-seh-rev5
* Windows-10-64bit
* CMake-3.12.0

```
General configuration for OpenCV 4.0.0-alpha =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2018-09-25T08:37:52Z
    Host:                        Windows 10.0.17134 AMD64
    CMake:                       3.12.0
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (4 files):          + SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (6 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (10 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++ Compiler:                E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/g++.exe  (ver 4.8.1)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann highgui imgcodecs imgproc java_bindings_generator ml objdetect photo python_bindings_generator shape stitching superres ts video videoio videostab
    Disabled:                    js world
    Disabled by dependency:      -
    Unavailable:                 java python2 python3 viz
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 1.5.3-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.34)
    TIFF:                        build (ver 42 - 4.0.9)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    Video for Windows:           YES
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 58.18.100)
      avformat:                  YES (ver 58.12.100)
      avutil:                    YES (ver 56.14.100)
      swscale:                   YES (ver 5.1.100)
      avresample:                YES (ver 4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-4.0.0-alpha/opencv-4.0.0-alpha/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            E:/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files (x86)/Java/jdk1.8.0_181/include C:/Program Files (x86)/Java/jdk1.8.0_181/include/win32 C:/Program Files (x86)/Java/jdk1.8.0_181/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-4.0.0-alpha/opencv-4.0.0-mingw64-build/install
-----------------------------------------------------------------
```

</details>

### [OpenCV 3.4.6](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.6) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.6.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.6.tar.gz)

```
git clone -b OpenCV-3.4.6 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86-7.3.0
* Windows-10-64bit
* CMake-3.14.1

```
General configuration for OpenCV 3.4.6 =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2019-07-22T17:25:51Z
    Host:                        Windows 10.0.18362 AMD64
    CMake:                       3.14.1
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/Qt/Qt5.13.0/Tools/mingw730_32/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2
      requested:                 SSE2
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX
      requested:                 SSE4_1 SSE4_2 AVX FP16
      SSE4_1 (15 files):         + SSE3 SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (6 files):             + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 AVX

  C/C++:
    Built as dynamic libs?:      YES
    C++11:                       YES
    C++ Compiler:                E:/Qt/Qt5.13.0/Tools/mingw730_32/bin/g++.exe  (ver 7.3.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/Qt/Qt5.13.0/Tools/mingw730_32/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         YES
    Extra dependencies:          opengl32 glu32
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann highgui imgcodecs imgproc ml objdetect photo shape stitching superres ts video videoio videostab
    Disabled:                    world
    Disabled by dependency:      -
    Unavailable:                 cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev java js python2 python3 viz
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    QT:                          YES (ver 5.13.0)
      QT OpenGL support:         YES (Qt5::OpenGL 5.13.0)
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 2.0.2-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.36)
    TIFF:                        build (ver 42 - 4.0.10)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 57.107.100)
      avformat:                  YES (ver 57.83.100)
      avutil:                    YES (ver 55.78.100)
      swscale:                   YES (ver 4.8.100)
      avresample:                YES (ver 3.7.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-3.4.6/opencv-3.4.6/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            C:/Users/huihu/AppData/Local/Programs/Python/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files/Java/jdk1.8.0_191/include C:/Program Files/Java/jdk1.8.0_191/include/win32 C:/Program Files/Java/jdk1.8.0_191/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-3.4.6/opencv-3.4.6-build/install
-----------------------------------------------------------------
```
</details>

### [OpenCV 3.4.5](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.5) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.5.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.5.tar.gz)

```
git clone -b OpenCV-3.4.5 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86-5.3.0
* Windows-10-64bit
* CMake-3.12.4

```
General configuration for OpenCV 3.4.5 =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2019-02-11T05:45:28Z
    Host:                        Windows 10.0.17763 AMD64
    CMake:                       3.12.4
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/Qt/Qt5.11.2/Tools/mingw530_32/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2
      requested:                 SSE2
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX
      requested:                 SSE4_1 SSE4_2 AVX FP16
      SSE4_1 (7 files):          + SSE3 SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (6 files):             + SSE3 SSSE3 SSE4_1 POPCNT SSE4_2 AVX

  C/C++:
    Built as dynamic libs?:      YES
    C++11:                       YES
    C++ Compiler:                E:/Qt/Qt5.11.2/Tools/mingw530_32/bin/g++.exe  (ver 5.3.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/Qt/Qt5.11.2/Tools/mingw530_32/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -mfpmath=sse -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         YES
    Extra dependencies:          opengl32 glu32
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann highgui imgcodecs imgproc java_bindings_generator ml objdetect photo python_bindings_generator shape stitching superres ts video videoio videostab
    Disabled:                    world
    Disabled by dependency:      -
    Unavailable:                 cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev java js python2 python3 viz
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    QT:                          YES (ver 5.11.2)
      QT OpenGL support:         YES (Qt5::OpenGL 5.11.2)
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 1.5.3-62)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.35)
    TIFF:                        build (ver 42 - 4.0.9)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 57.107.100)
      avformat:                  YES (ver 57.83.100)
      avutil:                    YES (ver 55.78.100)
      swscale:                   YES (ver 4.8.100)
      avresample:                YES (ver 3.7.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv-3.4.5/opencv-3.4.5/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            C:/Users/huihu/AppData/Local/Programs/Python/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files/Java/jdk1.8.0_191/include C:/Program Files/Java/jdk1.8.0_191/include/win32 C:/Program Files/Java/jdk1.8.0_191/include
    Java wrappers:               NO
    Java tests:                  NO

  Install to:                    E:/opencv-3.4.5/opencv-3.4.5-build/install
-----------------------------------------------------------------
```
</details>

### [OpenCV 3.4.1-x64](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.1-x64)  | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.1-x64.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.1-x64.tar.gz)

```
git clone -b OpenCV-3.4.1-x64 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x64-4.8.1-release-posix-seh-rev5
* Windows-10-64bit
* CMake-3.12.0

```
General configuration for OpenCV 3.4.1 =====================================
  Version control:               unknown

  Platform:
    Timestamp:                   2018-07-31T02:14:11Z
    Host:                        Windows 10.0.17134 AMD64
    CMake:                       3.12.0
    CMake generator:             MinGW Makefiles
    CMake build tool:            E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (3 files):          + SSSE3 SSE4_1
      SSE4_2 (1 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (2 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (9 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++11:                       YES
    C++ Compiler:                E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/g++.exe  (ver 4.8.1)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wno-narrowing -Wno-delete-non-virtual-dtor -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  E:/MinGW-w64/x64-4.8.1-release-posix-seh-rev5/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-narrowing -Wno-comment -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          opengl32 glu32
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann highgui imgcodecs imgproc java_bindings_generator ml objdetect photo python_bindings_generator shape stitching superres ts video videoio videostab
    Disabled:                    js world
    Disabled by dependency:      -
    Unavailable:                 cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev java python2 python3 viz
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build (ver 90)
    WEBP:                        build (ver encoder: 0x020e)
    PNG:                         build (ver 1.6.34)
    TIFF:                        build (ver 42 - 4.0.9)
    JPEG 2000:                   build (ver 1.900.1)
    OpenEXR:                     build (ver 1.7.1)

  Video I/O:
    Video for Windows:           YES
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (ver 57.107.100)
      avformat:                  YES (ver 57.83.100)
      avutil:                    YES (ver 55.78.100)
      swscale:                   YES (ver 4.8.100)
      avresample:                YES (ver 3.7.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            none

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)

  NVIDIA CUDA:                   NO

  OpenCL:                        YES (no extra features)
    Include path:                E:/opencv_341/opencv/sources/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            E:/Python37-32/python.exe

  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files (x86)/Java/jdk1.8.0_181/include C:/Program Files (x86)/Java/jdk1.8.0_181/include/win32 C:/Program Files (x86)/Java/jdk1.8.0_181/include
    Java wrappers:               NO
    Java tests:                  NO

  Matlab:                        NO

  Install to:                    E:/opencv_341/opencv_mingw64_build/install
-----------------------------------------------------------------
```

</details>

### [OpenCV 3.4.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.4.1) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.1.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.4.1.tar.gz)

```
git clone -b OpenCV-3.4.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86-5.3.0
* Windows-10-64bit
* CMake-3.9.2

</details>

### [OpenCV 3.3.1](https://github.com/huihut/OpenCV-MinGW-Build/tree/OpenCV-3.3.1) | [zip](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.3.1.zip) | [tar.gz](https://github.com/huihut/OpenCV-MinGW-Build/archive/OpenCV-3.3.1.tar.gz)

```
git clone -b OpenCV-3.3.1 git@github.com:huihut/OpenCV-MinGW-Build.git
```

<details><summary>Configuration</summary> 

* MinGW-x86-5.3.0
* Windows-10-64bit
* CMake-3.9.2

</details>

## Tutorials

### How to compile OpenCV

* [blog.huihut . OpenCV使用CMake和MinGW-w64的编译安装](https://blog.huihut.com/2018/07/31/CompiledOpenCVWithMinGW64/)
* [blog.huihut . OpenCV使用CMake和MinGW的编译安装及其在Qt配置运行](https://blog.huihut.com/2017/12/03/CompiledOpenCVRunInQt/)
* [wiki.qt . How to setup Qt and openCV on Windows](https://wiki.qt.io/How_to_setup_Qt_and_openCV_on_Windows)
* [Tutorial: Installation from source for Windows with Mingw-w64](http://visp-doc.inria.fr/doxygen/visp-daily/tutorial-install-win10-mingw64.html)

### Using OpenCV in Visual Studio Code

* [Running a C++ program with OpenCV 3.4.1 using MinGW-w64 g++ in Visual Studio Code on Windows 10 x64](https://stackoverflow.com/questions/51622111/opencv-c-mingw-vscode-fatal-error-to-compile/51801863#51801863)

### Using OpenCV in Visual Studio

* [How to build applications with OpenCV inside the Microsoft Visual Studio](https://docs.opencv.org/2.4/doc/tutorials/introduction/windows_visual_studio_Opencv/windows_visual_studio_Opencv.html)

### Using OpenCV in Qt
* [wiki.qt . How to setup Qt and openCV on Windows](https://wiki.qt.io/How_to_setup_Qt_and_openCV_on_Windows)