# 3D-Mapping-With-Dynamic-Object-Elimination
ROS based 3D mapping using KinectV1 with a method for Dynamic Object Elimination.

Our project implements a continuous real-time 3D mapping system that tackles the problem of point cloud distortion induced by dynamic objects in the frame. Our method uses the Microsoft Kinect V1 as the RGB-D camera and the packages in the Robotic Operating System (ROS) like the Real Time Appearance Based Mapping (RTAB-map) for 3D reconstruction. A ROS based method is used to implement dynamic object (person) elimination in real-time. For this Deep Learning based YOLO Object Detection was used. But due to less powerful system it was too slow to implement in realtime. Hence a face detection method was used to detect the RGB frames with person in it. 
