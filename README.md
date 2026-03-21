This project demonstrates how to simulate and detect common cyber attacks such as brute force login attempts and port scanning using a controlled lab environment

Tools used
1.kali linux
2.ubuntu
3.wirwshark
4.hydra
5.nmap

lab setup
 The lab consist of two virtual machines connected on the same network:
 attacker machine:Kali linux
 Target machine:Ubuntu
 
 Attacks simulated
 
 1.Brute-force attack using hydra 
 2.Port scanning using nmap
 
 Detection technoques
 .Monitering authentication logs (.var/log/auth.log)
 .Identifying multiple failed login attempts
 .Capturing TCP SYN packets using wireshark
 .Detecting abnormal traffic patterns 
 
 Response actions
 
 .flagging suspicious ip addresses
 .Blocking ip using firewall rules
 .Monitering for further malicious activities
 
 Key Learnings
 .Understanding  attack lifecycle (Recon exploit persistence)
 .Log analysis and correlation
 .Network traffic monitering
 .SOC detection techniques
 

