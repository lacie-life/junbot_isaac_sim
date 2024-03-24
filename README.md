# junbot_issac_sim

```bash
# For rosdep install command
sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential
# For colcon build command
sudo apt install python3-colcon-common-extensions

rosdep install -i --from-path src --rosdistro humble -y

colcon build
```

#### Importance note for simulation

```bash
export FASTRTPS_DEFAULT_PROFILES_FILE=<path_to_ros2_ws>/fastdds.xml # add this to extra param in Isaac Sim when start 
ros2 param set /rviz use_sim_time true
```



