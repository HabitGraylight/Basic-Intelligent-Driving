# Home Workshow
Habit Graylight(DuChengyi)
Biding(ChenPengyin)
Muze(LiangZimu)
## Comment
- data // two pcd files will be used in other codes
- Pc_Match // the code used to match point cloud data
- LIO_home // he main homework to finish, a LIO system, the main work to be done is in front_end.cpp
## Preparation
* Ubuntu 20.04
* ROS noetic(Recommonded Full Destop Version)
* PCL (Default Version with ROS)
* Eigen (Default Version with ROS)
* Glog ()
## Build
For Pc_Match
```sh
cd ~/Pc_Match/
mkdir build
cd build/
cmake ..
make
./optimized_icp
```
For LIO_home
```sh
cd ~/LIO_home/lio_icp/
catkin_make
source devel/setup.bash
```
