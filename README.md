NETWORK FOOTPRINTING & RECONNAISSANCE

Project Information

Field	Details
Project Title	Network Footprinting & Reconnaissance
Training Provider	NetworkWalks
Batch	B084
Module	W2-PM1
Student Name	Ogah Isaac
Target Domain	networkwalks.com
Operating System	Kali Linux
Project Type	Cybersecurity / Ethical Hacking
Focus Area	OSINT, Footprinting & Network Scanning


1. Liability Disclaimer

This project was conducted strictly for educational and practical learning purposes as part of the NetworkWalks cybersecurity training programme.

All reconnaissance and scanning activities must be performed within the scope of explicit authorization granted by the relevant system or network owner.

No unauthorized access, exploitation, disruption, or damage is intended or performed. Any security observations should be treated as learning points and not as confirmed vulnerabilities unless independently verified.


2. Introduction

Footprinting and reconnaissance are important early stages of ethical hacking and penetration testing. They involve gathering information about a target to understand its online presence, domain configuration, technologies, and network infrastructure.

This project explores different reconnaissance techniques using Kali Linux and industry-standard cybersecurity tools, with NetworkWalks as the intended target for authorized OSINT activities.

The exercise focuses on collecting publicly available information, identifying website technologies, discovering DNS records, and understanding network scanning techniques.

3. Project Objectives

* Understand the concept of footprinting and reconnaissance.
* Gather publicly available information about a target domain.
* Identify domain registration information.
* Examine DNS records and domain infrastructure.
* Identify technologies used by a website.
* Perform OSINT information gathering.
* Discover active hosts and network services within an authorized lab environment.
* Understand how reconnaissance findings can affect an organization’s security.
* Document technical findings and security recommendations.


4. Tools Used

Tool	Purpose
WHOIS	Retrieves publicly available domain registration information.
DIG	Queries DNS records and domain information.
WhatWeb	Identifies website technologies and frameworks.
theHarvester	Collects publicly available information from OSINT sources.
Zenmap	Provides a graphical interface for network scanning and host discovery.
Kali Linux	Operating system used for cybersecurity testing.


5. Activities Performed

5.1 WHOIS – Domain Information Gathering

WHOIS is a reconnaissance tool used to retrieve publicly available registration information about a domain.

Command:

whois networkwalks.com

Objectives:

* Identify domain registrar information.
* Examine domain creation and expiration details where publicly available.
* Review available name server information.
* Understand the information exposed through domain registration records.


5.2 DIG – DNS Information Gathering

DIG (Domain Information Groper) is a command-line tool used to query DNS records associated with a domain.

Commands:

dig networkwalks.com
dig networkwalks.com A
dig networkwalks.com MX
dig networkwalks.com NS
dig networkwalks.com TXT

Objectives:

* Identify available DNS records.
* Examine the domain’s IP address information.
* Identify mail exchange records.
* Review name server and TXT record information.
* Understand how DNS supports domain resolution.



5.3 WhatWeb – Website Technology Identification

WhatWeb is a website reconnaissance tool used to identify technologies and components associated with a website.

Command:

whatweb https://networkwalks.com

Objectives:

* Identify web server information where exposed.
* Detect content management systems where identifiable.
* Discover frameworks, libraries, and other technologies.
* Understand the website’s technology footprint.


5.4 theHarvester – OSINT Information Gathering

theHarvester is an OSINT tool used to collect publicly available information associated with a target domain from supported search sources.

Command:

theHarvester -d networkwalks.com -b duckduckgo

Objectives:

* Gather publicly indexed information.
* Identify publicly exposed email addresses where available.
* Discover associated hostnames and subdomains where returned.
* Understand how publicly available information supports reconnaissance.



5.5 Zenmap – Network Scanning and Host Discovery

Zenmap is the graphical interface for Nmap. It is used to perform network scanning, host discovery, and service identification.

Objectives:

* Discover active hosts within an authorized network.
* Examine open ports and detected services.
* Understand network visibility and scanning results.
* Practise interpreting network scan information.
* Identify potential network exposure.


Note: Zenmap results must reflect the actual lab network scanned. Do not present local lab scan results as findings about NetworkWalks unless that network was specifically included in the authorization.



6. Risk Analysis and Security Considerations

Footprinting and reconnaissance can reveal information that may help an attacker understand an organization’s digital infrastructure.

Area	Potential Security Concern	Security Recommendation
WHOIS	Public registration details may expose organizational information.	Use appropriate domain privacy protection where available.
DNS	Unnecessary DNS information may reveal infrastructure details.	Review DNS records and remove unnecessary records.
Web Technologies	Technology information may help attackers identify outdated components.	Keep software, frameworks, and plugins updated.
OSINT	Publicly exposed information may increase an organization’s attack surface.	Review public information and minimize unnecessary exposure.
Network Services	Unnecessary open ports may increase network exposure.	Disable unused services and restrict access to required ports.

These are general security considerations, not confirmed vulnerabilities discovered during this exercise.


7. Recommendations

* Regularly review publicly available domain information.
* Maintain accurate and secure DNS configurations.
* Keep website technologies and software components updated.
* Minimize unnecessary exposure of sensitive organizational information.
* Disable unused network services and ports.
* Use firewalls and access controls to restrict network exposure.
* Conduct authorized security assessments regularly.
* Monitor and investigate unusual reconnaissance or scanning activity.
* Maintain proper documentation of security assessment findings.


8. Conclusion

This project provided practical learning experience in network footprinting and reconnaissance using Kali Linux.

By exploring WHOIS, DIG, WhatWeb, theHarvester, and Zenmap, I gained a better understanding of how cybersecurity professionals gather information about domains, websites, and network environments.

The exercise reinforced the importance of reconnaissance as a foundational stage of penetration testing and highlighted how publicly available information can contribute to an organization’s overall security exposure.

It also strengthened my understanding of cybersecurity tools, information gathering, network scanning, and technical documentation.


9. Acknowledgement

I would like to express my appreciation to NetworkWalks for providing this practical cybersecurity learning opportunity.

Special thanks to my tutor, Waqas Karim (CCIE), for the guidance and support throughout the training.

This project has strengthened my practical understanding of cybersecurity, ethical hacking, and network reconnaissance.


10. Author Information

Author Name: Ogah Isaac
Training Provider: NetworkWalks
Batch: B084
Module: W2-PM1
Project: Network Footprinting & Reconnaissance

🔗LinkedIn:

Disclaimer: This report is intended for educational purposes and authorized security testing only.
