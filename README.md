# turtlebot_encrypted_control

노트북으로 깃 클론하는것 까지 했음
> 랩실 데스크탑으로 푸쉬하는걸 해야함

드디어 했다,,,,, 이게 add . 을 해주어야 git branch가 보이는거같기도하고\

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


