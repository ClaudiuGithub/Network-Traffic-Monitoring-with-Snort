# Network-Traffic-Monitoring-with-Snort
This project focuses on monitoring network traffic using the Snort intrusion detection system in a Kali Linux environment. The main objective is to simulate a basic network attack and observe how an IDS can detect suspicious or malicious activity in real time.
1. Installing Snort

Snort is installed on Kali Linux. The system confirms that the latest version is already available.<img width="1271" height="464" alt="snort instaled" src="https://github.com/user-attachments/assets/3cb6be16-562e-4e65-af9c-890844317cf7" />
2.Running Snort

Snort is started on the network interface eth0 in alert mode to monitor traffic in real time.<img width="1262" height="211" alt="snort running" src="https://github.com/user-attachments/assets/ced8af28-9ecb-41dc-831e-8ec6e4d5e4ff" />
3.Simulating the Attack (Ping)

A continuous ICMP ping is executed to simulate a simple network attack.<img width="1273" height="760" alt="attack  ping" src="https://github.com/user-attachments/assets/f8f82032-c2b2-425e-b294-dcc86ed6d5e5" />
4.<img width="1263" height="756" alt="snort detection" src="https://github.com/user-attachments/assets/6880d85a-169b-4d0c-bce5-270e35b316c7" />
Snort successfully detects the ICMP (ping) traffic based on its monitoring capabilities and configured rules. 
When the attack is running, Snort analyzes incoming packets in real time and generates alerts, indicating potential suspicious activity in the network.
5.Stoping the attack 
This <img width="1270" height="157" alt="stoping the attack " src="https://github.com/user-attachments/assets/27a4242a-9004-464f-a66c-d2cdf8e25b29" />
 shows the implementation of a firewall rule in Kali Linux using iptables to block ICMP (ping) traffic. The rule helps protect the system by preventing unwanted network probing and reducing the risk of certain network-based attacks
