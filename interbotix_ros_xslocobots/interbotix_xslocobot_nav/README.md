# interbotix_xslocobot_nav

[![View Documentation](https://docs.trossenrobotics.com/docs_button.svg)](https://docs.trossenrobotics.com/interbotix_xslocobots_docs/ros2_packages/navigation_stack_configuration.html)

## Overview

This package configures the ROS Navigation Stack needed to give any X-Series Interbotix LoCoBot platform the ability to perform simultaneous localization and mapping (SLAM), navigation, or just localization. It can be used with just the [Intel RealSense D435](https://www.intelrealsense.com/depth-camera-d435/) camera or with both the camera and the [A2M8 RPLidar](https://www.slamtec.com/en/Lidar/A2) laser scanner. The localization and mapping part is done using the [rtabmap_ros](http://wiki.ros.org/rtabmap_ros) ROS package while the navigation part is accomplished via the [move_base](http://wiki.ros.org/move_base) ROS package. For best results, this package should be run with the robot in an indoor, uncluttered environment that does not contain too much sunlight and has minimal reflective surfaces.
