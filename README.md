# rosautonamous-robot
ros melodic indoor auonamous robot
# setting up the project
clone the repository inside catki_ws in ros
#packages and dependencies
Ros- melodic ros-controlmager Gazebo  Navigation-stack in ros slam- gmapping
# Follow roswiki for ros  installation 
http://wiki.ros.org/melodic/Installation/Ubuntu
# check dependencies of the package
rosdep check <package name>
# install dependencies
rosdep install -i <package name>
  
  
  # Launching a file 
  
  roslaunch robot_description base_gazebo_control.launch
  
  roslaunch navigation mobile_manipulator_move_base.launch
  
  this will launch the robot and run navigation stack in ros
  
  # rosrun rviz rviz 
  to lauch the rviz 
  
  Try to play with the robot and change maps and  check the script file to send way point commands
  
 
 utilize the project and build scripts on it.
