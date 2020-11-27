<h1> ROS_beginner</h1>
Record my learning about ROS<br>

ROS安裝過程可以依照ROS官網步驟即可。<br>
ROS版本 : melodic<br>
安裝完記得要新增ros路徑<br>
'''<br>
$nano .bashrc<br>
$export catkin_ws/devel/setup.bash<br>
$export ROS_HOSTNAME = <br>
$export ROS_MASTER_URL = <br>
$source .bashrc <br>
$export TURTLEBOT3_MODEL=waffle_pi<br>
'''<br>
要執行ros navigation前需要先安裝缺少的套件:map_server, move_base, global_planner, teb_local_planner等<br>


<h2>建立工作區</h2>
mkdir -p mhh_ws/src
cd mhh_ws
catkin_make
cd
nano .bashrc

