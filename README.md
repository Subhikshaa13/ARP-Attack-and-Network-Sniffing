# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/14fa58ff-5cbb-419d-8155-faadf66fe132)





From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/aa9c0eea-51c3-4a92-bbce-7f3b23b3d3cd)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/394c47bb-b583-46b3-8e5f-5d6e1f24dee1)






In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/9ab45766-29c4-44b2-b674-fe15dd11f7e6)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/0949fd9c-a7f9-4565-b89e-8c582d7dcdc4)

##Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:


![image](https://github.com/Subhikshaa13/ARP-Attack-and-Network-Sniffing/assets/118787344/4b379d83-be95-4161-be15-e210d128ac12)

## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully
