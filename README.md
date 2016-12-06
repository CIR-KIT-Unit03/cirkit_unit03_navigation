# cirkit_unit03_navigation [![Build Status](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_navigation.svg?branch)](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_navigation) [![Slack](https://img.shields.io/badge/Slack-CIR--KIT-blue.svg)](http://cir-kit.slack.com/messages/unit03_navigation)
Navigation packages for CIR-KIT-Unit03.

## Installation
#### **!! CAUTION !!  DO NOT INSTALL** this repository **ALONE**.  
We highly recommend install this repository with [cirkit_unit03_pkgs](https://github.com/CIR-KIT-Unit03/cirkit_unit03_pkgs).

#### For the developers only
##### 1. Create **catkinized**  workspace.
##### 2. Clone this repository.
```bash
$ cd <catkin_ws>/src
$ git clone https://github.com/CIR-KIT-Unit03/cirkit_unit03_navigation.git
```

##### 3. Download depended packages by rosdep.
```bash
$ cd <catkin_ws>
$ rosdep install -i -r -y --from-paths src --ignore-src
```
##### 4. Build packages, and set the path for the packages.
```bash
$ cd <catkin_ws>
$ catkin_make
$ source devel/setup.bash
```
