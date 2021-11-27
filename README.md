# Second_assignmet Research Track 1


Introduction
================================

Robot simulator developed in ros environment in C++ language, the task of this assignmet make rotate robots in a Formula 1 track without touching the edges. All that is, you have to develop in this assignment, learn how to create a node in ros, how to use different packages in ros, use different servis in ros and know the type of servis or the format, how to implement a publisher and a subscriber in C++ language, how nodes communicate with each other, how to create a workspace in ros , how to use bashrc files and know the most important commands in ros.

Materials and Methods
=========================

This assignment was done by prof._Carmine Tommaso Recchiuto_ in course Reasearch track 1. All materials related to this course can be found on the website (https://2021.aulaweb.unige.it/course/view.php?id=4729) and to learn more about ros and learn from scratch check the website (http://wiki.ros.org/Documentation). The implemented method explained in the flowchat part and for startup part can refer to part Installing and running.

Installing and running
----------------------
After installing ros on the operating system(in my case operating system is a linux), you can proceed the following steps:
1. First step create my own workspace in my system : mkdir –p my_ros_ws/src
2. Enter new directory created : cd –p my_ros_ws/src
3. Download in zip format or use fork for your repositories or use : git clone https://github.com/Mohammadrezahajihosseini/Second_assignmet/blob/main/README.md
4. Back in root file : cd ..
5. Use : catkin_make (Catkin is the official build system of ROS and the successor to the original ROS build system, rosbuild)
6. Update setup.bash files to know new content : source devel/setup.bash
7. Use : roscore & (is the first thing you should run when using ROS).
8. Open the map where robots circulate :  
rosrun stage_ros stageros $(rospack find second_assignment)/world/my_world.world
