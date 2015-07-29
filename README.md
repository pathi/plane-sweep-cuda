# plane-sweep-cuda
**C++ plane sweep algorithm using CUDA**

At the moment only uses a fixed set of pictures and is not bug free. Some UI buttons do nothing.  
[CMakeLists.txt](https://github.com/DKavolis/plane-sweep-cuda/blob/master/src/CMakeLists.txt) 
will most likely need to be configured for your system.

**Libraries required:**
* [Qt 5.5](http://www.qt.io/) (only version with built-in RGB to grayscale conversion)
* [VTK](http://www.vtk.org/)
* [PCL](http://pointclouds.org/)
* [CUDA](https://developer.nvidia.com/cuda-zone)
* [boost](http://www.boost.org/)

**Optional libraries:**
* [OpenCV](http://opencv.org/)