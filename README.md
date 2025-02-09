# PCL_1.14_Framework_Build_for_iOS
## **Prebuilt iOS Framework for Point Cloud Processing**

⚠ **Note:** This build of PCL **excludes any libraries that depend on OpenMP or VTK**.  
PCL modules that require these dependencies have not been built to ensure compatibility with iOS.  
Additionally, I have not personally tested its use as a framework. If it does not work as expected,  
you may need to manually configure **search paths** and **library linking** in Xcode.  

---

## Included Prebuilt Libraries

The following prebuilt libraries are included in this repository:

- **PCL (Point Cloud Library)**: Built for iOS (static library).  
  Source: [Point Cloud Library (PCL)](https://github.com/PointCloudLibrary/pcl)
- **Boost**: Built using [boost-iosx](https://github.com/faithfracture/boost-iosx) (static library).  
  Source: [Boost C++ Libraries](https://github.com/boostorg/boost)
- **FLANN**: Built for iOS (static library).  
  Source: [FLANN (Fast Library for Approximate Nearest Neighbors)](https://github.com/mariusmuja/flann)
- **Qhull**: Built for iOS (static library).  
  Source: [Qhull](http://www.qhull.org/)
- **LZ4**: Built for iOS (static library).  
  Source: [LZ4](https://github.com/lz4/lz4)
- **Eigen**: Header-only library (included directly in the project).  
  Source: [Eigen](https://gitlab.com/libeigen/eigen)

All prebuilt libraries are distributed in compliance with their respective licenses. See the `licenses` folder for details.
  
## Licensing
This project is licensed under the MIT License. See the LICENSE file for details.

Each prebuilt library is subject to its own license. See the licenses folder for the full text of each license:

- **PCL (Point Cloud Library)** - BSD License
- **Boost** - Boost Software License 1.0
- **FLANN** - BSD License
- **Qhull** - BSD-style License
- **LZ4** - BSD License
- **Eigen** - MPL2 License
