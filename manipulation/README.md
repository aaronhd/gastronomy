# gastronomy/manipulation

The manipulation repository consists of 2 packages.

## Robot-Interface

The Robot-Interface package in the robot-interface folder was created by Mohit Sharma and Kevin Zhang to control the Franka Panda Research Robot and the UR5e and was used for the Dynamic Motion Primitives (DMP) cutting demo. In addition, CAD models that were 3D printed to hold the knife and mount cameras to the robot are included in the robot-interface/CAD Models folder.

## Plating

The Plating package in the plating folder was created by Travers Rhodes to learn trajectories from demonstrations that are used in the plating demo. It can be used with any robot that has a ROS joint controller interface. It includes code to segment demonstrations using a changepoint detection algorithm, and it contains code to translate and execute those trajectories on a robot.
