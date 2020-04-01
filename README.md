# 612-Project

To get the repository via command line use the following command in the "src" folder of a catkin workspace:
```
git clone https://github.com/Lilweavs/robot_simulation.git
```
To build the workspace, make sure you are in a catkin workspace directory then run:
```
catkin build
```
Navigate to ~/{your_ws} and source the workspace:
```
source devel/setup.bash
```
All the code is ready to run now. First start a roscore:
```
roscore
```
Now open a new terminal and re-source your workspace. Then start a empty gazebo world using:
```
roslaunch gazebo_ros empty_world.launch
```
Open another terminal and re-source your workspace. Finally load the models to simulate run:
```
roslaunch robot_simulation spawn.launch
```
