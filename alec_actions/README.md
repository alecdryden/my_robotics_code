# ROS package: |alec_actions|

The *alec_actions* package features a client-service interaction where responses could take a significant amount of time. In this case, action server provides feedback of the actual elapsed time after receiving a goal to output every second. It is seen that the results are not exact, but the package has a self-correctly method it uses for accuracy.

## Requirements

This package is meant to run on a Linux Ubuntu. It was made using ROS Melodic.

## Installation and configuration

This package should be imported into the src (source) folder of your ROS project alongside other packages.

## Getting started

This package can be executed with a launch file. **First, make sure to run the line `source devel/setup.bash` before launching the package.**

Also, after adding the packages to your ROS project, run `catkin_make` to make a new build that includes the new package.

## Usage

Input the following syntax to run the package from the launch file: `roslaunch alec_actions fancy_action.launch`

The launch file will output a series of elapsed and remaining times up to five seconds.
