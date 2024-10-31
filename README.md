# Lab-14-Performing-and-Detecting-CSRF
 
Lab Overview
In this lab, I performed a Cross-Site Request Forgery (CSRF) attack and investigated the results. As a cybersecurity analyst at Structureality Inc., my goal was to identify weaknesses and vulnerabilities that needed to be addressed within our internal network.

Scenario
I executed a CSRF attack on the public-facing website of Structureality Inc., which was hosted within the screened subnet. After performing the attack, I analyzed the website logs to find evidence and Indications of Compromise (IoCs) related to CSRF activities.

Environment Setup
Virtual Machines
KALI: This virtual machine ran Kali Linux, which I used to carry out the CSRF attack.
LAMP: This virtual machine ran Ubuntu Server and hosted the DVWA (Damn Vulnerable Web Application) website. I utilized this VM for the investigation after the attack.
Objectives
This lab was designed to enhance my understanding and application of the following CompTIA CySA+ objectives:

System and Network Architecture:

1.1 Explained the importance of system and network architecture concepts in security operations.
Malicious Activity Indicators:

1.2 Analyzed indicators of potentially malicious activity given a scenario.
Tools and Techniques:

1.3 Used appropriate tools or techniques to determine malicious activity given a scenario.
Threat Intelligence vs. Threat Hunting:

1.4 Compared and contrasted threat intelligence and threat-hunting concepts.
Mitigation Controls:

2.4 Recommended controls to mitigate attacks and software vulnerabilities given a scenario.
Incident Response:

3.2 Performed incident response activities given a scenario.
Attack Methodology Frameworks:

3.5 Explained concepts related to attack methodology frameworks.
Lab Instructions
Preparation:

Ensured that both KALI and LAMP virtual machines were running and accessible.
Performing the CSRF Attack:

Used the KALI VM to execute a CSRF attack on the DVWA site hosted on the LAMP VM.
Investigating the Logs:

After completing the attack, I switched to the LAMP VM.
Accessed the web server logs and searched for any indicators of the CSRF attack.
Documentation:

Recorded notes on identified vulnerabilities and any evidence of the CSRF attack.
Analyzed the logs for potential IoCs.
Conclusion
This lab was crucial for deepening my understanding of CSRF attacks and recognizing the importance of proactive security measures in web applications. The skills acquired supported my ability to identify and mitigate vulnerabilities within the organization’s infrastructure.
