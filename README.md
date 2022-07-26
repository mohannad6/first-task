# first-task

(download ros on linux)

If Windows operating system:

 The first thing is install 
  
VirtualBox 6.1.36 :
 https://www.virtualbox.org/wiki/Downloads 


After we open virtual box we create  a new operating system and then we choose the settings that match our pc parts then start the operation
system and choose ubuntu-22.04-desktop-amd64

and now download ros noetic 


 open terminal and we type down the following commands from this link :

http://wiki.ros.org/noetic/Installation/Ubuntu






(download ROS in jetson nano)

The first thing is install  
  Xubuntu version 20.04 L4T R32.3.1  


using the etcher program 
  We set up the system that we downloaded:
Flash image


In the event that the version of the Jetson Nano A02, we connect the sd card to the Jetson Nano and turn it on, and the usual installation screen will appear and we will complete the installation process

But if the version of the Jetson Nano B01 is, we need to go to the SD card file called extlinux.conf and open it in the terminal and write this command:

sudo vim extlinux.conf

  We add this line:

boot/tegra210-p3448-0000-p3449-0000-b00.dtb

And save the file

And then the same thing, we connect the card to the Jetson Nano and it turns us on the installation screen

But as for ROS we just paste the commands from Foxy Fitzroy on terminal the commands
