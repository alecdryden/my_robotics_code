# ROS package: |alec_topics|

The *alec_topics* package features publisher-subscriber interactions where the publisher node outputs sequential integers (1,2,3,etc.) continuously. The subscriber nodes subscribes to that topic and prints the data published by the publisher node.

## Requirements

This package is meant to run on a Linux Ubuntu. It was made using ROS Melodic.

## Installation and configuration

This package should be imported into the src (source) folder of your ROS project alongside other packages.

## Getting started

This package can be executed with a launch file. **First, make sure to run the line `source devel/setup.bash` before launching the package.**

Also, after adding the packages to your ROS project, run `catkin_make` to make a new build that includes the new package.

## Usage

Input the following syntax to run the package from the launch file: `roslaunch alec_topics fancy_topic.launch`

The launch file will continuously output sequential integers continuously until the program is stopped.
