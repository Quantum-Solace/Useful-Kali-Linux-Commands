# Useful-Kali-Linux-Commands
This is just a simple showcase of my favourite linux commands, I will be updating this list periodically.

Favourite commands
___________________

**run command with superuser priviledges**

sudo  

**run last command as sudo**

sudo !! 

**run command as a background process**

nohup 

&

**check background jobs**

bg

**print local ip addresses**

ifconfig

ip a

ip addr

ip address

<!-- print wifi cards and their status -->

iwconfig

iw dev

<!-- print public ip address -->

curl ifconfig.me

<!-- print $PATH -->

echo $PATH

<!-- print environments -->

env

<!-- print background processes --> 

ps aux

top 

htop

<!-- print network ports and connections -->

netstat -a

<!-- download files from a website -->

wget

curl -o

<!-- check for wifi card -->

iwconfig

iw dev

<!-- hcxdumptool & hcxpcaptool for hashcat WPA2 PMKID cracking and hash conversion -->

hcxdumptool -i <interface> -w <outputfile> -F --rds=1 --beacontx=10 --gpsd

hashcat -m 22000 <file.hc22000> -a 3 ?d?d?d?d?d?d?d?d?d?d

<!-- start nessus --> 
sudo systemctl start nessusd.service

open browser at https://localhost:8834

<!-- virus scanners and rootkithunter -->

clamtk

rkhunter --check
