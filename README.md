# Stereo-Vision-based-SLAM
Indoor/Outdoor SLAM using Stereo Vision. This project used ORB_SLAM2 with ZED stereo camera to achieve the task of SLAM and has a custom 2D occupancy grid mapping algorithm using depth.

Dependencies:
1. DepthToLaserScan - some of the header files from this package have been used. They are already added to this repo.
2. zed-ros-wrapper : compile and build as per the guidlines on https://github.com/stereolabs/zed-ros-wrapper .  In the launch file change the confidence parameter (80 was used here), also the depth range was clipped to 3 meters
3. ORB_SLAM2 : The original work was posted by Raulmur (https://github.com/raulmur/ORB_SLAM2) which this project builds on.
