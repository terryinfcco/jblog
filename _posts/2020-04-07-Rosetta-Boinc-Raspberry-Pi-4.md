---
layout: post
categories: server RaspberryPi
---

So I’m going to try to get going with running Boinc and Rosetta on my Pi4. First I have to install Ubuntu Server (since Raspbian is only 32 bit, Rosetta won’t work on Raspbian). I’m trying 18.04 LTS first, and am going to try to ssh into it. I’ve read that the trick that works on Raspbian of putting a file called ssh into the boot partition works on Ubuntu also. And I’m going to edit etc/hostname to call the computer pi4boinc.

Finally I’m going to use the instructions at https://www.cnx-software.com/2020/04/06/rosettahome-now-supports-64-bit-arm-sbcs-and-servers-in-the-fight-against-covid-19/ to install boinc and rosetta from the command line.

Sort of works, I got boinc installed, but wasn’t able to add Rosetta as a project. So I added yoyo and that works. I’ll try Rosetta later. And it works a few minutes later!!
