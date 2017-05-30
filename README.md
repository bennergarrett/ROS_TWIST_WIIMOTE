# teleop_twist_wiimote
Wiimote Teleop revised from Generic Keyboard Teleop for ROS  

#Install

To run:  
```
        sudo apt-get update    
        sudo apt-get install python-cwiid   
        mkdir -p ~/catkin_ws/src  
        cd catkin_ws/src  
        git clone https://github.com/bennergarrett/teleop_twist_wiimote
        cd ~/catkin_ws/src/teleop_twist_wiimote
        chmod +x teleop_twist_wiimote.py
        sudo apt install dos2unix
        dos2unix teleop_twist_wiimote.py
        cd ~/catkin_ws  
        catkin_make
```
#Launch  
You need to make sure you have a roscore running.  


To run:  
```
         cd ~/catkin_ws  
         . devel/setup.bash  
         rosrun teleop_twist_wiimote teleop_twist_wiimote.py  
```
#Usage  

How to use wiimote button  

```
        1 + 2 simultaneously = connect raspberry pi to wiimote
        up = forward
        down = reverse
        left = turn left
        right = turn right
        home button = quit/disconnect
```
