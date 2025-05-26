# Task 1
Tools
nmap
wireshark


Step 1

To find open ports in local network devices I used nmap tool

command:
        nmap -sS 192.168.43.0/24
 
result:

      Nmap scan report for LAPTOP-MI24DF9H (192.168.43.23)
      Host is up (0.00016s latency).
      Not shown: 999 filtered tcp ports (no-response)
      PORT     STATE SERVICE
      3306/tcp open  mysql

Step 2

open wireshark , right click on eth0 then start capture

we can see ARP packets are sent from our source ip to the target ips to the devices in our local network.
After that TCP packets are transmitted.
