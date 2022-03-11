# Red-Team-vs.-Blue-Team-Project

I worked on a Red Team vs. Blue Team scenario in which I played the role of both pentester and SOC analyst.

As the Red Team, I attacked a vulnerable VM within my environment, ultimately gaining root access to the machine. As Blue Team, I used Kibana to review logs taken during the Day 1 engagement. I used the logs to extract hard data and visualizations for my report.

Then, I interpreted my log data to suggest mitigation measures for each exploit that I successfully performed.


In this project, I applied knowledge of the following skills and tools:


Penetration testing with Kali Linux.

Log and incident analysis with Kibana.

System hardening and configuration.

Reporting, documentation, and communication.


Lab Environment

In this unit, I used the Red vs Blue lab environment located in Windows Azure Lab Services. 
Opened the Hyper-V Manager to access the nested machines:

ELK machine credentials: The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
Username: 
Password: 
IP Address: 192.168.1.100


Kali: A standard Kali Linux machine for use in the penetration test on Day 1.
Username: 
Password: 
IP Address: 192.168.1.90


Capstone: Filebeat and Metricbeat are installed and will forward logs to the ELK machine.
IP Address: 192.168.1.105
Please note that this VM is in the network solely for the purpose of testing alerts.
