# Dummy ROS OpenRAVE Package
This is a dummy ROS OpenRAVE package that creates links for the OpenRAVE installation so ROS is aware of the path of the OpenRAVE software.

This pacakge can be useful if you are installing [UR5 OpenRAVE Controller](https://github.com/papallas/ur5controller).

# Preparation
If you are coming from the [UR5 OpenRAVE Controller](https://github.com/papallas/ur5controller) I assume that you have already configure your `rosmake_ws` **if not** then follow the following steps:
- Create a new directory called `rosmake_ws` in your home directory. `mkdir ~/rosmake_ws`
- Edit your `~/.bashrc` file located under your home directory: `gedit ~/.bashrc` and add the following line at the end of the file: `export ROS_PACKAGE_PATH=$ROS_PACKAGE_PATH:~/rosmake_ws`
- Run `source ~/.bashrc`.

# Installation
- Clone this repository in your `rosmake_ws` and then run `rosmake`:
  ```bash
  cd ~/rosmake_ws
  git clone git@github.com:papallas/openrave.git
  cd openrave
  rosmake
  ```

You should see a quick make process and then a successful message in which case you are ready and finished.
