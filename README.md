# TryHackMe Walkthrough

![Logo](https://assets.tryhackme.com/img/THMlogo.png  "Logo")

This repository contains a few of my writeups I made of the TryHackMe CTF (Capture The Flag) challenges.

**TryHackMe Profile :** [0xr001](https://tryhackme.com/p/0xr001)

The folder names are the names of the Challenges. Every folder is containing a **README.md** file with the Walkthrough in it. It also includes any file ,logs, scans etc. in the subfolder which belongs to the challenge. Click on the desired Folder and Get Hacking.

The Walkthrough **DOES NOT** contain the **FULL FLAG**. Parts of the Flag is censored due to ***Learning Purposes.***

## Setup Your Environment

- Download [Viritual box](https://www.virtualbox.org/wiki/Downloads)
- Download [Kali Linux 64 bit](https://www.kali.org/get-kali/#kali-virtual-machines)
- Install and run Viritual Box
- Create a new machine
- Choose "Other Linux"
- Go to machine settings
- Mount the kali linux file as the hdd, remove the other one
- Launch the machine
- The default credentials "username :- kali, password :- kali"

## Connect To Tthe VPN

- Download the configuration file [here](https://tryhackme.com/access)
- Open the terminal

```bash
~$ sudo openvpn your-username.ovpn
```

##### Find more information on the TryHackMe website: <https://tryhackme.com>