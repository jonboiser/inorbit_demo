# Installation

1. Setup
```bash
source /opt/ros/noetic/setup.bash
cd ~/Code/catkin_ws
git clone https://github.com/jonboiser/inorbit_demo.git
catkin_make
```
1. Install InOrbit agent
1. Change custom scripts location

```bash
# this will override the previous export
printf '\nexport INORBIT_ACTIONS_PATH="%s/user_scripts"\n' $(pwd) >> ~/.inorbit/local/agent.env.sh
```
4. Start `roscore` in one terminal
1. Run this app in another terminal

```
source ~/Code/catkin_ws/devel/setup.bash
```
