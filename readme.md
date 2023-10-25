!!! IN PROGRESS 

## Installation
1. Clone this repo into /root/roboboat_ws/
2. add `export GZ_SIM_RESOURCE_PATH=/root/roboboat_ws/vrx_packages:$GZ_SIM_RESOURCE_PATH` to the end of your bashrc file
3. Run `. ~/.bashrc`
4. Copy sydney_regatta.sdf to /src/vrx/vrx_gz/worlds/
cp sydney_regatta /root/robobat_ws/src/vrx/vrx_gz/worlds/
Run ros2 launch vrx_gz competition.launch.py world:=sydney_regatta