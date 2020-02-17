The file rqt_mypkg is a package that I am trying to build in order to create an rqt pluggin for ROS.

I have been following the tutorials found here:

http://wiki.ros.org/rqt/Tutorials/Create%20your%20new%20rqt%20plugin

http://wiki.ros.org/rqt/Tutorials/Writing%20a%20Python%20Plugin

I follow the tutoral and I am able to get the package to build but when I try to run the code using:

`rosrun rqt_mypkg rqt_mypkg`

I get the error:

[rospack] Error: package 'rqt_mypkg' not found

I try:

`rqt --force-discover`

but I still get the same error.


I am using a machine running Ubuntu 16.04 and ROS Kinetic