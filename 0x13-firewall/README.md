Firewall
In this project, I used ufw to configure firewalls on my issued web servers.

Useful recap notes about firewall
:

What is a firewall?
A hardware or software security system.
What are the 2 types of firewall? -Network and host-based firewall.
What is the main function of a firewall? -To filter incoming and outgoing network traffic.
Tasks
0. Block all incoming traffic but

0-block_all_incoming_traffic_but: Bash script that installs a ufw firewall to block all incoming traffic except for ports 22, 443 and 80 on a web server.
1. Port forwarding

100-port_forwarding: ufw configuration file that configures a firewall to redirect port 8080/TCP to port 80/TCP
