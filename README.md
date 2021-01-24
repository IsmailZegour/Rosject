# AUTORS
Marouane KHANDALI | Pierre BOURDEAU | Ismail ZEGOUR - Gr 1

# INSTALLATION

- Create a Kinetic ROSJect

- Dans WhebShell #1 : 
```bash
rm -rf ~/catkin_ws
rm -rf ~/simulation_ws
git clone https://github.com/mar1git/ROSject.git ~/catkin_ws
git clone https://github.com/ceri-num/LARM-RDS-Simulation-WS.git ~/simulation_ws
cd ~/catkin_ws/
catkin_make
source devel/setup.bash
cd ~/simulation_ws/
catkin_make
source devel/setup.bash
```

# CHALL 1

- WebShell #1 : `roslaunch larm challenge-1.launch`

- WebShell #2 : `roslaunch students_package navigation.launch`

- WebShell #3 : `rosrun rviz rviz`

- Dans rviz : File -> Open Config -> Open "/home/user/catkin_ws/rviz/challenge1.rviz"

- Control the turtlebot via RVIZ...


# CHALL 2

- WebShell #1 : `roslaunch larm challenge-2.launch`

- WebShell #2 : `roslaunch students_package mapping.launch`

- WebShell #3 : `rosrun rviz rviz`

- Dans rviz : File -> Open Config -> Open "/home/user/catkin_ws/rviz/challenge2.rviz"

- Control the turtlebot via RVIZ...

- Bottles position is published in the /bottle topic : `rostopic echo /bottle`


# CHALL 3

En cours...
