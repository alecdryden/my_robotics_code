# ROS package: |alec_actions|

|Short introductory paragraph about your package. What does it do? Why is it useful?|

## Requirements

This package is meant to run on a Linux Ubuntu. It was made using ROS Melodic.

## Installation and configuration

This package should be imported into the src (source) folder of your ROS project alongside other packages.

## Getting started

This package can be executed in two ways: 1) from a launch file or 2) from manually running nodes, as discussed in the next section. **First, make sure to run the line `source devel/setup.bash` before launching the package.**

Also, after adding the packages to your ROS project, run `catkin_make` to make a new build that includes the new package.

## Usage

### 1) Running the package with launch file
Input the following syntax to run the package from the launch file: `roslaunch alec_services fancy_service.launch my_args:="..."`

Replace "..." with your arguments. The launch file was edited to accept input by the client node, utilizing the package's word counting feature. Unfortunately, the package still outputs log information and adds it to the word count.

### 2) Running the package manually
Start by running `roscore` in a terminal window.
