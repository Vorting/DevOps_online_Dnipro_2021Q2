Part 1. Hypervisors
1. The most popular HyperVisors are VMwawre, Microsoft and Orcal.
2. Both the VMware and Hyper-V are paid hypervisors using for corporate segments.VMware functions on Windows and Linux, but not use on Mac. Hyper-V only for Windows. Virtual-Box is free product using on all mentioned OS.    

Part 2. Work with VB

2.1. I got acquainted with user manual VB. Download VB.exe and install it on my pc with W10.

2.2 I downloaded latest version of Ubuntu 20.04 and installed it according to the manual in chapter 1.8 on my VM1. I also acquainted with the possibilities of VM1 such as start, stop, reboot, save state used Host (right Ctrl) and keyboard shortcuts, mouse etc. Then I cloned it to VM2.

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_1.png)

2.3 I configured the usb to connect the usb-ports of the host machine [ch.3.11] and configured shared folder from win10 to virtual machine. On screenshots 2,3,4 and 5 you can see shared folder "Desktop_W10" in "/media/sf_Desktop_W10" and plugged usb-drive in /dev/sdb1 in "/media/vorting/CENTOS-8-2"
![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_2.png) 

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_3.png)

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_4.png)

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_5.png)

Part 3.work with vagrant

3.1. I downloaded vagrant_2.2.13_x86_64, because with latest version I've got error with key. I checked at vagrant path in the Environment Variables.
3.2 In the powershell I created folder in "C:\" and named it "vagrant_test".
![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_6.png)

3.3. In "vagrant_test" I initialized the environment with default Vagrant box using the comand: "init hashicorp/precise64".Then I run VM created with vagrant, looked for the messages. When my vagrant_test virtual machine loaded I connected to it using putty, with default both username and password.
![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_7.png)

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_8.png)

When I completed my tusks, I stopped and deleted my VM.

![](https://github.com/Vorting/DevOps_online_Dnipro_2021Q2/raw/main/m2/task2.1/screenshots/screenshot_9.png)
