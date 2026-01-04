深蓝学院移动机器人路径规划作业3——RRT_star_planner

一、安装依赖 \
1、去官网下载ompl源码 \
https://ompl.kavrakilab.org/download.html \
<img width="580" height="312" alt="image" src="https://github.com/user-attachments/assets/0cbaf6b0-192d-4dc7-a779-e819d3d524e0" />


cd ompl-1.7.0\
mkdir -p build\
cd build\
cmake ..\
make -j 4

二、安装
catkin_make \
source devel/setup.bash \
roslaunch grid_path_searcher demo.launch \


<img width="1851" height="957" alt="image" src="https://github.com/user-attachments/assets/cdc653a6-4440-48db-91b8-acfb93afe3a2" />
