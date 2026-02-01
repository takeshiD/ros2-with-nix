# ROS2 with Nix
Easy start ROS2 with nix.

# Getting Started
```bash
git clone https://github.com/takeshid/ros2-with-nix.git
cd ros2-with-nix
```

## into devShell
```bash
nix develop
# building ros2 desktop...(about 30min~)
```

## if you use `direnv`
```bash
cp .envrc.sample .envrc
direnv allow
```

## Run demo
```bash
ros2 run demo_nodes_cpp talker
[INFO] [1769928732.964199501] [talker]: Publishing: 'Hello World: 1'
[INFO] [1769928733.964187027] [talker]: Publishing: 'Hello World: 2'
[INFO] [1769928734.964220475] [talker]: Publishing: 'Hello World: 3'
[INFO] [1769928735.964164805] [talker]: Publishing: 'Hello World: 4'
[INFO] [1769928736.964206317] [talker]: Publishing: 'Hello World: 5'
[INFO] [1769928737.964217343] [talker]: Publishing: 'Hello World: 6'
[INFO] [1769928738.964247142] [talker]: Publishing: 'Hello World: 7'
[INFO] [1769928739.865935676] [rclcpp]: signal_handler(signum=2) # cancell by Ctrl-C
```
