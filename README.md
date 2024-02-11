# DDOS-ATTACK-ICMP Flooding
# About
ICMP flooding, also known as ICMP flood attack or Ping flood attack, is atype of Distributed Denial of Service (DDoS) attack that targets the ICMP(Internet Control Message Protocol) protocol. ICMP is primarily used for diagnostic and error reporting purposes in IP networks. 

The primary goal of an ICMP Flood DDoS attack is to exhaust the target system's resources, leading to degraded performance or a complete denial of service. The sheer volume of incoming ICMP requests can overload the target's network infrastructure, making it difficult for legitimate traffic to reach its destination. As a result, the target may experience slow response times, service interruptions, or even a complete shutdown.
# Requirements
- Python 
# Target Website
The website that we have chosen to attack for the purpose of this project is https://www.hackthissite.org/ (which is a legal training ground to practice ethical hacking). 
# Usage
1. Firstly, start by pinging the website we wish to perform the DDoS attack on to understand how it responds to requests prior to the attack.
2. Then execute a Python code that aids in sending packets and helps stimulate the ICMP flood attack.
3. Enter the IP address of the website that we are performing the attack on, and follow it up by entering the number of packets to be sent to the website’s server as a ping flood, which is an exorbitantly high number.
4. Ping the website’s server again to observe the difference in response post-attack.
# Observation
This simulation demonstrates how servers are unable to handle requests from legitimate users when it is being overwhelmed with requests from a malicious hacker using ping floods. It disrupts the regular functioning of the website’s operations, thereby causing several damages and financial losses for the organization.
