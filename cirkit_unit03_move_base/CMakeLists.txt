cmake_minimum_required(VERSION 2.8.3)
project(cirkit_unit03_move_base)
find_package(catkin REQUIRED COMPONENTS roslaunch)

roslaunch_add_file_check(test/move_base.test.xml)
roslaunch_add_file_check(test/move_base_gazebo.test.xml)
