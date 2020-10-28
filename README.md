<h1> ROS_beginner
Record my learning about ROS

ROS安裝過程可以依照ROS官網步驟即可。
ROS版本 : melodic
安裝完記得要新增ros路徑
'''
$nano .bashrc
$export catkin_ws/devel/setup.bash
$source .bashrc 
$export TURTLEBOT3_MODEL=waffle_pi
'''
要執行ros navigation前需要先安裝缺少的套件:map_server, move_base, global_planner, teb_local_planner等
