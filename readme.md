#setup

execute with sudo or without as root
sudo apt-get install conky conky-all curl lm-sensors hddtemp

enable conky on startup in xfce by adding new 
entry in 
Settings > Session and Startup > Application Autostart 

with field values
Name: Conky  
Description: Conky  
Command:/home/\<user\>/.config/conky/conky_startup.sh

replace \<user\> with particular user name
