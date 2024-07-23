# Run-Turtlesim-package-Ros2-
Here I will Run Turtlesim package in Ros2 humble 



1-Check environment variables

by using this command:


```
printenv | grep -i ROS
```
<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-١٧ في ٦ ٥٠ ٠٣ ص" src="https://github.com/user-attachments/assets/6b7b5565-a1e7-4c12-8a9e-9f9220e69f39">

2- Install the turtlesim package in ros2


by using this command:

```
sudo apt update
sudo apt install ros-humble-turtlesim
```
<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-١٧ في ٦ ٥١ ٥٠ ص" src="https://github.com/user-attachments/assets/b79c821f-e0a3-40fc-99d2-d7b68fc2d249" >



3- Check that the package is installed

by using this command:

```
ros2 pkg executables turtlesim
```
<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-١٧ في ٦ ٥٢ ٥٨ ص" src="https://github.com/user-attachments/assets/dd46d8dc-a1fd-47aa-8ac8-83825e08ca20" >


4-Run turtlesim node


by using this command:

```
ros2 run turtlesim turtlesim_node
```
<img width="1440" alt="‏لقطة الشاشة ١٤٤٦-٠١-١٧ في ٦ ٥٦ ٣٠ ص" src="https://github.com/user-attachments/assets/fdc76caa-f9f3-4d60-b117-2acae16afde0">



5- Run turtle teleop node in new terminal


by using this command:
```
ros2 run turtlesim turtle_teleop_key
```
![‏لقطة الشاشة ١٤٤٦-٠١-١٧ في ٧ ٠٥ ٠٩ ص](https://github.com/user-attachments/assets/39080a1e-5124-4521-8181-7046d85e0778)

