# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
### NAME:SANJAY ASHWIN P
### REG NO:212223040181
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
![WhatsApp Image 2024-10-15 at 19 01 00_0703393d](https://github.com/user-attachments/assets/95b73a22-ea9a-40ac-889d-a3f372259986)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![WhatsApp Image 2024-10-15 at 18 58 45_717129e2](https://github.com/user-attachments/assets/f45e2fb2-a20e-4254-a4ef-e09786632ea0)

### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![WhatsApp Image 2024-10-15 at 19 20 47_567781f5](https://github.com/user-attachments/assets/8834b550-a9d6-401d-8d91-4a07a6fc4f4b)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![WhatsApp Image 2024-10-15 at 19 16 13_87dac05e](https://github.com/user-attachments/assets/a6a92c67-6da2-4482-a93e-f92a98c2c132)



Invoke the wireshark and examine the various menus  and controls of the tool:
![WhatsApp Image 2024-10-15 at 18 36 59_c6254078](https://github.com/user-attachments/assets/c366f6af-e56f-400d-a485-1432955494c0)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
