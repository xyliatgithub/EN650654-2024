# Lab 5 - Security Onion 

## Overview
In this lab, we will explore **Security Onion**, free and open source platform used for intrusion detection, security monitoring, and log management.


## Lab Environment Setup

<img src="https://github.com/E-Alahmadi/CID_SO_Lab/blob/main/Network%20Setup.png" width="1000">

In this lab, you will have two networks: 
1. **Management Network:** For increased security in an enterprise setting, it is a common practice to separate the management traffic and production traffic. This is achieved by configuring a dedicated management network (DMN) that is used only for administrative access. In which, management traffic is carried independently of traffic over the production network, making management significantly more reliable. This network is used by network administrators to access and configure network resources, such as switches, servers, and routers. In addition to performing software updates and performance monitoring.

2. **Monitor Network:** In an enterprise setting we want to monitor the production network. This is done using Intrusion Detection Systems to monitor the production network and generate alerts for any malicious, anomalous, or otherwise suspicious traffic. 

Lastly, for this lab you will need five VMs. The Analyst VM will be connected to the Management Network whereas the Attacker, Server and User VMs will be connected to the Monitor Network. At the same time, Security Onion VM will be connected to both networks.

## Lab Structure 
The minimum hardware requirements for this lab are more than the hardware capabilities of most personal machines. Please, use one of the MSSI Lab machines to perform this lab. Additionally, please go through these documents **in order**.

1. **[Analyst VM Installation:](...)** Follow this manual to install and configure the Analyst VM.
2. **[Security Onion VM Installation:](...)** Follow this manual to install and configure the Security Onion VM.
3. **[Attacker VM Installation:](...)** Follow this manual to install and configure the Attacker, Server, and User VMs.
4. **[Security Onion Console:](...)** Explore Security Onion Console (SOC). 
5. **NIDS Scenario:** Examine how Security Onion could be utilized as a Network-Based Intrusion Detection System. 
6. **HIDS Scenario:** Examine how Security Onion could be used as a Host-Based Intrusion Detection System. 