# ahrs
Receiving data from AHRS in Raspberry pi, then publish to topside PC.

# Raspberry pi setup
ssh to raspberry pi (password: ```raspberry```)
```
ssh pi@192.168.2.2
```
open docker
```
docker start lala
docker exec -it lala /bin/bash #
```
setup multi ros
```
source /opt/ros/noetic/setup.bash
cd root
source multi
cd ahrs_ws
catkin_make
```

# Topside PC setup
setup multi ros
```
source multi
roscore
```