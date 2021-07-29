# CBF ROS package
Before running the code, follow the instructions in `cbf_ros` folder to install the HSR ROS packages on your Ubuntu system. 

## How to run the code?
1. Copy `Tjanction.world` under `~/cbf_ros/worlds` folder 
2. Open two instances of MATLAB. In one instance, open `main.m` and in the other one open `cbf_controller.m`. 
3. Open a terminal in your ubuntu system and type `ifconfig`. Then, copy the ip address under `eno1` and change the ip address of `rosinit('http://ip address:11311')` with the copied address in `main.m` and `cbf_controller.m` scripts. 
4. Run the simulator in Gazebo. 
5. Run `cbf_controller.m` in MATLAB. 
6. Run `main.m` in the other MATLAB instance. 
