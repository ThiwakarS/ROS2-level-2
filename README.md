## Project insights
- I have been following a udemy course, to learn on the Robotic Operating system 2.
- With the level 2 of that course I learnt the following things:
-> How to create a urdf file defining a robot and its description.
-> How to use ROS2 in conjunction with Gazebo classic 11 and GZ harmonic
-> Learnt a lot on links, joints, collision, inertia, urdf, xacro, RViz and worlds.
-> How to create a launch file and launch the project with a single line of code.

- I have also made a final project "My robot bringup" which does the following things:
-> Creates a robot description on the /robot_description topic.
-> launches rviz with the robot defined in the topic.
-> Spawns the robot in gazebo with a world in the worlds directory
-> We can start the simulation, to check out the physics simulation in gazebo.
-> We can move the robot by sending a command to /cmd_vel topic.

- It was such a great experience going through, to set up ubuntu  and ROS2 with the help of this udemy course: https://www.udemy.com/course/ros2-tf-urdf-rviz-gazebo/

- To verify my certificate on completion of this course, you can visit: https://www.udemy.com/certificate/UC-7dd80c79-357a-4c60-99a9-01e257e577d3/

## Execution of the project
- To run this project for yourself, create a ROS2 workspace,
- Compile it with colcon build, and go to the src directory.
- Then place these folders on the src directory, and again build the workspace.
- Now in the terminal, run
```bash
ros2 launch my_robot_bringup my_robot_gz.launch.py
```

## Project structure
```
├── ros2_ws/
│    ├── include/
│    ├── build/
│    ├── log/
│    ├── src/
│        ├── my_robot_description/
│        └──  my_robot_bringup/
```
