rtabmap ![Analytics](https://ga-beacon.appspot.com/UA-56986679-3/github-main?pixel) 
=======

<a href="http://introlab.github.io/rtabmap"><img src="https://raw.githubusercontent.com/introlab/rtabmap/master/guilib/src/images/RTAB-Map.png" align="center" height="100"></a>

[![Release][release-image]][releases]
[![License][license-image]][license]
Linux: [![Build Status](https://travis-ci.org/introlab/rtabmap.svg?branch=master)](https://travis-ci.org/introlab/rtabmap) Windows: [![Build status](https://ci.appveyor.com/api/projects/status/hr73xspix9oqa26h/branch/master?svg=true)](https://ci.appveyor.com/project/matlabbe/rtabmap/branch/master)

[release-image]: https://img.shields.io/badge/release-0.14.0-green.svg?style=flat
[releases]: https://github.com/introlab/rtabmap/releases

[license-image]: https://img.shields.io/badge/license-BSD-green.svg?style=flat
[license]: https://github.com/introlab/rtabmap/blob/master/LICENSE

RTAB-Map library and standalone application.

For more information, visit the [RTAB-Map's home page](http://introlab.github.io/rtabmap) or the [RTAB-Map's wiki](https://github.com/introlab/rtabmap/wiki).

To use RTAB-Map under ROS, visit the [rtabmap](http://wiki.ros.org/rtabmap) page on the ROS wiki.


For this specific version isntallation:
1. Have freenect installed

2. cmake command:
   cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=~/rtabmaplib/ -Dfreenect2_DIR=$HOME/freenect2/lib/cmake/freenect2  ..
