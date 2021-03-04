# 2021_DKU_OS


This is a place for studying Operaing System in Dankook University.
- Professor : Jongmoo Choi
- Assistant : Hojin Shin (Email : ghwls03s@gmail.com)
- 2021 DKU Operating System Course Information [link](http://embedded.dankook.ac.kr/~choijm/course/course.html)


## Download Environment
Virtual Machine Platform: VirtualBox 6.1.18

[VirtualBox Download Link](https://www.virtualbox.org/wiki/Downloads)

Windows Subsystem for Linux Install Guide (WSL)

[WSL Install Guide Link](https://docs.microsoft.com/ko-KR/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package)

Operating System: Ubuntu 20.04

This environment is based on VirtualBox 6.1.18
If image execution is not possible, we recommend reinstalling VirtualBox 5.2 version.

[Virtual Box 5.2 Link](https://www.virtualbox.org/wiki/Download_Old_Builds_5_2)

## Clone Git Repository
git clone https://github.com/DKU-EmbeddedSystem-Lab/2021_DKU_OS.git

If you get an error there are no commands, install git with following command :

sudo apt-get install git

## Lab0

lab0 contains information about installing a virtual machine and Ubuntu.

Set the environment according to the documentation.

The documentation for lab0 is at the link below.

The OS image to use for preferences is also on the link below.

Documentation for conducting the assignment can be found at following link :

[Lab0 Documentation Link](https://drive.google.com/file/d/1wVn5F4VII52AuR7_dPml5srA5a7ZzTzh/view?usp=sharing)

DKU OS Image Download Link [Link](https://drive.google.com/file/d/11vOOjmYY-kWOY2u1andpluxYBdSQT-EA/view?usp=sharing)


## Lab1
If you want to proceed to Lab1, go to command below :

cd lab1_sched

make

./lab1_sched

Documentation for conducting the assignment can be found at following link :

[Lab1 Documentation Link](https://drive.google.com/file/d/1mYGDew24HVDfdBL1VkqQuCpRC9JRzaKU/view?usp=sharing)

## Lab2
If you want to proceed to Lab2, go to command below :

Will be update Soon

See the documentation for details.

Documentation for conducting the assignment can be found at following link :

[Lab2 Documentation Link]()

## Lab3

If you want for proceed to Lab3, go to command below :
cd lab3_filesystem

make

insmod ramdisk.ko

mkdir mnt

mkfs.fat -F 32 /dev/ramdisk

mount /dev/ramdisk ./mnt

./create.sh

See the documentation for details.

[Lab3 Documentation Link]()

Bonus Image Link : [IMAGE_LINK](https://drive.google.com/open?id=1nDOef1QCtXNO49R87IVuYgpwCOdOsPK7)
