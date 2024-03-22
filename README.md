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
ros2 param set /rviz use_sim_time true
```



