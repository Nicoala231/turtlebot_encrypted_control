# turtlebot_encrypted_control

# Requirement
ros2 (현:foxy)
turtlesim package

# Usage
1. 터틀봇 두개 소환하는 런치 파일 실행
```ros2 launch turtle_demo_controller two_turtle.launch.py```

2. 터틀봇1을 움직일 노드파일 실행
new terminal:  
```$ ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args --remap /cmd_vel:=/turtle1/cmd_vel ```

3. leader-follower 노드 실행
new terminal:  
```
$ ros2 run turtle_demo_controller leader_follower
```

# Reference

https://github.com/roboticvedant/ROS2_turtlesim_PID_demo

