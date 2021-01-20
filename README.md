# AUTORS
Marouane KHANDALI | Pierre BOURDEAU | Ismail ZEGOUR - Gr 15

# INSTALLATION

- Créer un ROSJect Kinetic

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
- Dans WebShell #2 et #3 :
```bash
cd ~/catkin_ws/
source devel/setup.bash
cd ~/simulation_ws/
source devel/setup.bash
```

# CHALL 1

- WebShell #1 : `roslaunch larm challenge-1.launch`

- WebShell #2 : `roslaunch challenge challenge-1.1.launch`

- WebShell #3 : `rviz`

- Dans rviz : File -> Open Config -> Open "/home/user/catkin_ws/rviz/map.rviz"

- Naviguer avec la carte dans rviz...



# CHALL 2

En cours...
