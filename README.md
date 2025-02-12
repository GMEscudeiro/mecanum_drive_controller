
# Mecanum drive controller

A controller for mecanum drive robots for ros2_control.
It is based on diff_drive_controller providing wheel velocities and odometry.
Made for ROS2 Humble.




## Installation

Clone this repository in your workspace:

```bash
  cd ~/ros2_ws/src
  git clone https://github.com/GMEscudeiro/mecanum_drive_controller.git
```
Then build it using colcon and source the overlay:

```bash
  cd ~/ros2_ws
  colcon build --symlink-install
  source install/setup.bash
```


## Usage/Examples

Follow the steps in [Running the Framework for your Robot](https://control.ros.org/master/doc/getting_started/getting_started.html#running-the-framework-for-your-robot) before using the package.

The parameters can be found inside the src folder in mecanum_drive_controller_parameter.yaml

