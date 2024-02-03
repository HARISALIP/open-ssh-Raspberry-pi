# open-ssh-Raspberry-pi
How to setup open ssh in RASPBERRY PI


open ssh Raspberry pi

1 - installed ubuntu 22.04

2 - sudo apt update

3 - haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ sudo apt install openssh-server 

4 - haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ sudo systemctl status ssh

5 - haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ ssh haris@192.16
    haris = user name
    
    
    
haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ ssh haris@192.168
ssh: Could not resolve hostname 192.16: Name or service not known
haris@haris-HP-Pavilion-Laptop-15t-xx000:~$ ssh haris@192.16
The authenticity of host '192.168 (192.168.)' can't be established.
ED25519 key fingerprint is SHA256:cQnOjEysfCJRnkEW48LVqPrQvf8LAlFtiXmA.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '192.16' (ED25519) to the list of known hosts.
haris@192.168.'s password: 
Welcome to Ubuntu 22.04.3 LTS (GNU/Linux 5.15.0-4-raspi aarch64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

Expanded Security Maintenance for Applications is not enabled.

225 updates can be applied immediately.
164 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable

Enable ESM Apps to receive additional future security updates.
See https://ubuntu.com/esm or run: sudo pro status


The programs included with the Ubuntu system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Ubuntu comes with ABSOLUTELY NO WARRANTY, to the extent permitted by
applicable law.

haris@haris-desktop:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  snap  Templates  Videos
haris@haris-desktop:~$ cd Downloads/
haris@haris-desktop:~/Downloads$
haris@haris-desktop:~/Downloads$ 

