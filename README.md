# robond-go_chase_it
## OverView 
![Ball_Chaser](images/ball_chaser.png)

## Build Robot Model from URDF

After finished the robot model, check syntax by `check_urdf`
```
$ check_urdf <(xacro --inorder my_robot.xacro)
```

Careful for the misspell and this caused the robot unbalanced.

![misspell](images/misspell.PNG)

![Unblanced Robot](images/unbalance_robot.png)

## Analyzing the Images
![Analyzing Image](images/analyze-image.png)

* Known the difference between `img.width` and `img.step` . [Image Message](http://docs.ros.org/melodic/api/sensor_msgs/html/msg/Image.html)


* Known how the 3 channels images data stored


## DEMO Video: Go Chase It!

[![Go Chase It](http://img.youtube.com/vi/r7r8TiZP5Z8/0.jpg)](http://www.youtube.com/watch?v=r7r8TiZP5Z8 "Go Chase It!")
