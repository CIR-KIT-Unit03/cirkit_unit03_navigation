# cirkit_unit03_navigation [![Build Status](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_navigation.svg?branch=kinetic-devel)](https://travis-ci.org/CIR-KIT-Unit03/cirkit_unit03_navigation) [![Slack](https://img.shields.io/badge/Slack-CIR--KIT-blue.svg)](http://cir-kit.slack.com/messages/unit03_navigation)


## Summary
Navigation packages for CIR-KIT-Unit03 indluding navigation, localization, SLAM, and map storage.

For CIR-KIT-Unit03 instructions and tutorials, please see http://wiki.ros.org/Robots/CIR-KIT-Unit03.

- cirkit_unit03_amcl : [amcl](http://wiki.ros.org/amcl) (localization) configurations and launch files.
- cirkit_unit03_gmapping : [gmapping](http://wiki.ros.org/gmapping) (SLAM) configurations and launch files.
- cirkit_unit03_maps : Storage space of maps.
  - By default, only sample maps are stored here.
  - ***We'll never add additional maps in git*** in order to reduce storage size of the repository.
- cirkit_unit03_move_base : [move_base](http://wiki.ros.org/move_base) (navigation) configurations and launch files.

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
