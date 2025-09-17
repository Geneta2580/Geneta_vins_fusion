# VINS-Fusion with comment
## VINS-Fusion: Easy-to-use version for VIO Study

Platform: Ubuntu 20.04

Type: Plug-and-play / Ready-to-run

Dependencies: Requires only fishros and Ceres.
(fishros can be obtained by `wget http://fishros.com/install -O fishros && . fishros`
 we use ros-noetic and Ceres v2.0.0)

Features: Includes Chinese comments in the source code.

Purpose: Intended for learning and studying VIO.

## Running VINS-Fusion

1. Create a ROS Workspace
If you don't have one already, create a Catkin workspace.

3. Clone the Repository
Clone this project into the src folder of your workspace.

4. Compile the Code
Navigate to your workspace directory and compile the project using `catkin_make`.

5. Run the VINS Node
Open a new terminal, source your workspace, and run the vins_node with your configuration file. Remember to source the setup file first.
```bash
source ~/catkin_ws/devel/setup.bash
rosrun vins vins_node <path_to_your_config_file>/config.yaml
```

6. Play the Dataset
Open another terminal and play your ROS bag file.
```bash
source ~/catkin_ws/devel/setup.bash
rosbag play your_dataset.bag
```
## Citation
https://github.com/fishros/install  
https://github.com/HKUST-Aerial-Robotics/VINS-Fusion  
https://github.com/ceres-solver/ceres-solver/releases/tag/2.0.0  
