# Log

  *Init
=====

Tab spaces 2 in settings

  *Github/Bitbucket Reposisitory

$ git config --global user.name "kappa"
$ git config --global user.email "kappajester83@gmail.com"
$ git config --global color.ui auto
$ git config --global pull.rebase false

$ echo "# Labs" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin https://github.com/Kapaajester83/Labs.git
$ git push -u origin main

user: kappa
pass: "user key" provided by Github/Bitbucket

  *ovpn
=====

GUI
"+" import from file
navigate to extracted .opvpn file

CLI
cd/ [directory].opvpn

*CTRL+C to close terminal and end sesstion

    *Virtualbox
===

https://www.virtualbox.org/
https://www.vmware.com/

https://www.kali.org/get-kali/#kali-platforms
https://www.parrotsec.org/

User Notes:

VirtualBox vs VMware

VolnHub may have specific requirements, but in general they both work the same.  My experience is that VMware is a little more robust and stable, but also requires additional "host computer" resouces.  VirtualBox seems to be faster with smaller "host computer" resources.  

Kali Lunix vs ParrotOS

Kali GUI will feel similar to Linux users while ParrotOS can be closer to Mac.  Parrot seems to have more options out of the box, and Kali may require download for special apps. 

For that reason I prefer the long term versions for lab exercises as VM's allow you to allocate available disk usage and RAM from you local machine.  As this will be a live operating system, reducing time to update software packages are less time consuming than the weekly option.  

For private jobs the "weekly option," and project specific, with an ending time period is awesome.

I will be using Kali Linux and VirtualBox for the purpose of this repo, as currently working on a legacy computer with limited resources.

Debian: 64-Bit
RAM: 4GB
Video: 1GB
Disk: 80GB
Network: NAT


