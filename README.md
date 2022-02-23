# 0nhc edited.
# For ROS Noetic

```sh
cd catkin_ws/src
git clone --recursive https://github.com/0nhc/rslidar_sdk.git
cd rslidar_sdk
git submodule init
git submodule update
sudo apt-get update
sudo apt-get install -y libyaml-cpp-dev libpcap-dev libprotobuf-dev protobuf-compiler
cd ..
cd ..
catkin_make
```
