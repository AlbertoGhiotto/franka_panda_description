# franka_panda_desctiption 

Package modified from *franka_description* package ([*franka_ros*](https://github.com/frankaemika/franka_ros])) to provide gazebo simulation support. This package is needed for [*panda_simulator*](https://github.com/justagist/panda_simulator).

## Related Packages
- [*panda_simulator*](https://github.com/justagist/panda_simulator) : Simulation in Gazebo with exposed controllers and state feedback using ROS topics and services. The simulated robot uses the same ROS topics and services as the real robot when using the [*franka_ros_interface*](https://github.com/justagist/franka_ros_interface).
- [*franka_ros_interface*](https://github.com/justagist/franka_ros_interface) : A ROS API for controlling and managing the Franka Emika Panda robot (real and simulated). Contains controllers for the robot (joint position, velocity, torque), interfaces for the gripper, controller manager, coordinate frames interface, etc.. Provides almost complete sim-to-real transfer of code.
- [*panda_robot*](https://github.com/justagist/panda_robot) : Python interface providing higher-level control of the robot integrated with its gripper, controller manager, coordinate frames manager, etc. It also provides access to the kinematics and dynamics of the robot using the [KDL library](http://wiki.ros.org/kdl).