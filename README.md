## NOTE: UR5Controller is now a catkin package, as such you should create a catkin workspace and build ur5controller as a catkin package.

# Dummy ROS OpenRAVE Package
This is a dummy ROS OpenRAVE package that creates links for the OpenRAVE installation so ROS is aware of the path of the OpenRAVE software.

# Installation
- Clone this repository in your `rosmake_ws` and then run `rosmake`:
  ```bash
  cd ~/rosmake_ws
  git clone git@github.com:papallas/openrave.git
  cd openrave
  rosmake
  ```
