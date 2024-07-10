**ros2 moveit 2 node elephant robotics mycobot 320pi**

This is moveit2 node for mycobot320pi (ros2)

*****URDF SETTING & INSTALLATION*****

download both ros-noetic and ros-humble repository provided by elephant robotics

for ros2, move mycobot_description into the src and remove all the files under urdf folder

copy all the files from mycobot_description/urdf/mycobot_320pi_moveit under ros-noetic repository, and paste it into your workspace's mycobot_description/urdf/mycobot_320pi.

change the names to
"mycobot_320_pi_2022.urdf"
"mycobot_320_pi_moveit_2022.urdf"
"mycobot_vision_v2_2022"

colcon build, source setup.bash and enjoy!


Once built, run for the test 
> ros2 launch mycobot320pi-moveit demo.launch.py

rviz should launch with robot model loaded. 
