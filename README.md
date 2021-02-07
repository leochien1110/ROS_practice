# ROS_practice


#Instructions for Compiling viznav Software

## 1. Create workspace
Create a directory called **ROS_practice** where you normally put your source code (usually git)
```
        cd ROS_practice
        mkdir src
        cd src
        git clone git@github.com:leochien1110/ROS_practice.git
```

## 2. Build workspace
```
        cd ../..
        catkin_make
```    
"catkin_make" twice to build the msg/srv first.

## 3. To Create a new package/folder
```
        catkin_create_pkg <package_name> [depend1] [depend2] [depend3]
	ex: catkin_create_pkg beginner_tutorials std_msgs rospy roscpp
```    
