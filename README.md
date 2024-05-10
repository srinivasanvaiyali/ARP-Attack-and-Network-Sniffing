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

![image](https://github.com/srinivasanvaiyali/ARP-Attack-and-Network-Sniffing/assets/145117665/203c1f56-777c-4c71-99c0-9333be6820ff)

From kali linux issue the command : sudo arpspoof -i eth0 -t

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/srinivasanvaiyali/ARP-Attack-and-Network-Sniffing/assets/145117665/82731454-40f1-405f-b3c0-927bd96ed669)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/srinivasanvaiyali/ARP-Attack-and-Network-Sniffing/assets/145117665/43ff9de3-8f66-4902-9a93-19b08c5467d2)




Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/srinivasanvaiyali/ARP-Attack-and-Network-Sniffing/assets/145117665/dac782d1-6646-4abe-98a1-4f69847bd663)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
