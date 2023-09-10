# ITU-ZES-SCT-Qualification-2023
ITU-ZES-SCT-Qualification-2023

This workspace is tested in ROS Humble under Ubuntu Linux 22.04.

For installing ros-humble, you can install from [this link](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)

For testing, firstly clone this repo and go to workspace directory.
```
$ git clone https://github.com/ITU-ZES-Solar-Car-Team/ITU-ZES-SCT-Autonomous-Driving-Team-Qualification-2023.git
$ cd ITU-ZES-SCT-Autonomous-Driving-Team-Qualification-2023/itusct_assignment_ws
```

Source the ros galactic's source file and try to build this workspace. You will get compile error. That's what you should try to solve it.
```
$ source /opt/ros/humble/setup.bash
$ colcon build
```
