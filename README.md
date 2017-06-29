# kukavarproxy Message Format

## 1. Description


## 2. How it works


## 3. Usage
The KRC4 robot controller runs the Microsoft Windows 7 operating system. The teach pendant shows an “HMI” which is a program that KUKA developed to run on Windows and it is the interface that the robot user has to manipulate the robot through.
In order to establish an Ethernet (TCP/IP) connection, you first need to run kukavarproxy on the controllers operating system, then configure the network connection from KUKA "HMI".
###   3.1. Copying kukavarproxy to the operating system on the KRC:
* Get the kukavarproxy from https://sourceforge.net/projects/openshowvar/files/openshowvar/REV%200.13.0/kukavarproxy-6_1.rar/download
* Copy the folder to a USB flash drive
* Plug it to the KRC (not the teach pendant)
* Loging as an Expert or an Administrator `KUKA Menu -> Configuration -> User Group). Defaulf password is kuka`
* Minimize the "HMI" `KUKA Menu -> Startup -> Service -> Minimize HMI`
* Copy kukavarproxy folder to the Desktop (or anywhere else)
* Start the KUKAVARPROXY.exe
* If you have a problem with the file `cswsk32.ocx`, Use this command in the Administrator Command Prompt `regsvr32.exe asdf\cswsk32.ocx` while changing the `asdf` with the true path to the file.
###   3.2. HMI Network Configuration:
* 
* 

https://www.robodk.com/forum/attachment.php?aid=4

## 4. Resources
* http://sourceforge.net/projects/openshowvar/
* https://github.com/aauc-mechlab/jopenshowvar/
* http://filipposanfilippo.inspitivity.com/publications/jopenshowvar-an-open-source-cross-platform-communication-interface-to-kuka-robots.pdf
* https://www.robodk.com/forum/attachment.php?aid=4