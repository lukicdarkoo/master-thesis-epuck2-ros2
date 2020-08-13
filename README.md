# ROS2 Programming Interface for the E-puck2 Robot

<p align="center">
  <img width="400px" src="_template/project_logo.png">
</p>

This is a report for my master's project about [ROS2](https://index.ros.org/doc/ros2/) programming interface for the [e-puck2 robot](https://www.gctronic.com/doc/index.php/e-puck2).

> Robotics simulations have been proven to be a powerful tool for developing a robot controller as they are easy to set up, cheap, fast, and convenient to use.
However, the final objective is usually to deploy the controller on the real robots or even to run the controller on an arbitrary robot.
This thesis presents a ROS2 driver for e-puck2 physical robots and a generalized ROS2 driver for Webots simulated robots. 
The ROS2 drivers expose a nearly identical ROS2 interface that allows a controller to interact in the same way with the physical e-puck2 and the simulated robots without changes.
Effectively, it allows the controller developers a seamless transition between simulated and physical e-puck2 robots or other simulated robots.
The ROS2 drivers are validated in multiple scenarios, like navigation and mapping.
The results prove that researchers can quickly validate their ROS2 controllers on the e-puck2 physical or simulated robot and other Webots simulated robots.

## Code

The code for this project is available across multiple repositories:
- [cyberbotics/epuck_ros2](https://github.com/cyberbotics/epuck_ros2): ROS2 interface for the physical robot, the main contributor ([PRs](https://github.com/cyberbotics/epuck_ros2/pulls?q=is%3Apr+author%3Alukicdarkoo+is%3Aclosed+closed%3A%3C2020-08-14), [graph](https://github.com/cyberbotics/epuck_ros2/graphs/contributors?from=2020-02-17&to=2020-08-14)).
- [cyberbotics/webots_ros2](https://github.com/cyberbotics/webots_ros2): ROS2 interface for simulated robots, introduced automatic ROSification ([PRs](https://github.com/cyberbotics/webots_ros2/pulls?q=is%3Apr+author%3Alukicdarkoo+is%3Aclosed+closed%3A%3C2020-08-14), [graph](https://github.com/cyberbotics/webots_ros2/graphs/contributors?from=2020-02-17&to=2020-08-14)).
- [cyberbotics/webots](https://github.com/cyberbotics/webots): Introduced improvements to Webots core needed for automatic ROSification ([PRs](https://github.com/cyberbotics/webots/pulls?q=is%3Apr+author%3Alukicdarkoo+is%3Aclosed+closed%3A%3C2020-08-14), [graph](https://github.com/cyberbotics/webots/graphs/contributors?from=2020-02-17&to=2020-08-14))
- [lukicdarkoo/epuck-ros2-various-analyses](https://github.com/lukicdarkoo/epuck-ros2-various-analyses): Data analysis, benchmarks, camera calibration and similar.
