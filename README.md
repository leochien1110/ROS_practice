# ROS_practice


#Instructions for Compiling viznav Software

## 1. Install GSL (GNU Scientific Library)
```
        sudo apt install libgsl-dev
```

## 2. Install GTSAM
```
        sudo apt-add-repository ppa:borglab/gtsam-develop
        sudo apt update
        sudo apt install libgtsam-dev libgtsam-unstable-dev
```

## 3. Create workspace
Create a directory called **flashlight** where you normally put your source code (usually nea_src)
```
        cd flashlight
        mkdir src
        cd src
        git clone ssh://git@bb.nearearth.us:7999/flas/viznav.git
```

## 4. Build workspace
```
        cd ../..
        catkin_make
```    
