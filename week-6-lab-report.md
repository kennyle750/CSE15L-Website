# Lab Report #3

## Streamlining ssh Configuration

* First step, to set up streamlining ssh, you want to locate your ssh files within your system.
* So open up the terminal, and type in these commands
<br/> cd ~
<br/> cd .ssh/
<br/> touch config
* This creates the config file on your local machine.
* Now type these commands.
<br/>**ls** 
<br/> **pwd**
![Image](configcommand.png)

* After your directory for ssh is open, click on it to open up the folder. Within this folder you shall see a file called config. Now what you want to do is edit that file based on this format below. 
<br/>**Host (host)**
<br/>**HostName (HostName)**
<br/>**User (your username)**
* In other words, it should look something like this with ieng6.
![Image](configpic.png)
* After you have edit the config file using Notepad for windows or in VSCode for Linux, save it and open your terminal.
* Now all you have to do njow to log into your remote machine is just type in **ssh ieng6**, **ieng6** being your host.
* Now you can remotely log in faster by just tying in the host name instead of the entire username of yours!
![Image](sshlogin.png)

---

## Setup Github Access from Ieng6

---

## Copy whole directories with scp -r
* scp -r is a command that lets you copy files from your local machine into your remote machine.
* 