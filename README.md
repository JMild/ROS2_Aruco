# ROS2_Aruco
These are packages for using Intel RealSense cameras (D400, L500 and SR300 cameras) with ROS2.

This version supports ROS2 Foxy, and Humble.

## How To Use Aruco Marker with RealSense Camera
### Requisites:
- [realsense-ros](https://github.com/IntelRealSense/realsense-ros)

### Start the camera node
To start the camera node in ROS:

  ```bash
    ros2 launch realsense2_camera rs_launch.py
  ```
Open new terminal for start the ar_marker node in ROS:
  ```bash
    ros2 run (package_name) aruco_node.py
  ```  
  
### Published Topics
Running the `ros2 topic list` command in a new terminal will return a list of all the topics currently active in the system

To see the data being published on a topic, use `ros2 topic echo (topic)`

  -  /aruco_id: 
  -  /aruco_pose: 
 
      
