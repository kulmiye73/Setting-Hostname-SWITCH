# Setting-Hostname-SWITCH
![image](https://github.com/kulmiye73/Setting-Hostname-SWITCH/assets/60412799/80f01dfd-959d-4a26-ae5e-4f0166ffef78)




## Configuring Hostname and Descriptions on a Switch

conf t
hostname SW1
description Sales Department
## Setting password for Switch
line console 0
password switch
logging synchronous
# Configuring VTY lines
line vty 0 15
password switch
login
# Setting the Message of the Day (MOTD) banner
banner motd # Welcome Sales Dept#

