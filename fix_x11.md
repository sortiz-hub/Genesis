sudo apt update
sudo apt install x11-xserver-utils
sudo apt install xvfb
sudo Xvfb :0 -screen 0 1024x768x16 &
export DISPLAY=:0
xhost +local:root