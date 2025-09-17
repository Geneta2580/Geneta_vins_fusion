# VINS-Fusion with comment
## VINS-Fusion: Easy-to-use version for VIO Study

Platform: Ubuntu 20.04

Type: Plug-and-play / Ready-to-run

Dependencies: Requires only fishros and Ceres.
(fishros can be obtained by 'wget http://fishros.com/install -O fishros && . fishros')

Features: Includes Chinese comments in the source code.

Purpose: Intended for learning and studying VIO.

## Running VINS-Fusion
'''bash
catkin_make

'''bash
rosrun vins vins_node config.yaml
rosbag play xxx.bag

## Citation
