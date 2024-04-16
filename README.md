<h1> Incident Report: NIST Cybersecurity Framework for Network Security</h1>

<h2>Description</h2>
In this activity, I will analyze a situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The CSF is a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Creating a quality cybersecurity incident report and applying the CSF can demonstrate a proactive approach to security, improve communication and transparency with stakeholders, and improve security practices within your organization.
<br /> <br />
The Five Functions of the Cybersecurity Framework are: <br /> <br />

•	IDENTIFY security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential security gaps.

•	PROTECT internal assets through the implementation of policies, procedures, training, and tools that help mitigate cybersecurity threats.

•	DETECT potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.

•	RESPOND to contain, neutralize, and analyze security incidents; implement improvements to the security process.

•	RECOVER affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 
<br />

<h2>Scenario</h2>


I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, my organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve my company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).
<br/> <br/>


<h2>Summary</h2>

The multimedia company experienced a Distributed Denial of Service (DDoS) attack, resulting in a two-hour disruption of internal network services. The attack involved a flood of ICMP pings overwhelming the network through an unconfigured firewall. The incident was mitigated by blocking incoming ICMP packets, halting non-critical network services, and restoring critical services. To prevent future attacks, the organization implemented new firewall rules, source IP address verification, network monitoring software, and an IDS/IPS system.

<h2>Identify </h2>

•	Type of Attack: Distributed Denial of Service (DDoS) Attack.

•	Impact: Internal network services stopped responding for two hours.

•	Attack Source: A malicious actor sent a flood of ICMP pings through an unconfigured firewall.

•	Targeted Systems: Internal network services and resources.

•	Response: Blocking incoming ICMP packets, stopping non-critical network services offline, restoring critical network services, implementing new firewall rules, source IP address verification, network monitoring software, and IDS/IPS system.
<br /> <br />

<h2>Protect</h2>

To further protect the organization's assets, the following actions should be taken:<br /> <br />
1.	Regularly review and update firewall configurations to ensure all security measures are properly configured and up to date.
2.	Conduct comprehensive security training for employees to raise awareness about cybersecurity threats, including DDoS attacks, and emphasize the importance of following security policies and procedures.
3.	Implement strict access control policies to limit access to critical network resources and sensitive data only to authorized personnel.
4.	Regularly audit and update network infrastructure to identify and address any potential vulnerabilities or misconfigurations that could be exploited by malicious actors.
<br />

<h2>Detect</h2>

To enhance detection capabilities and monitor network traffic effectively, the following steps can be taken:<br /> <br />
1.	Deploy advanced network monitoring tools capable of analyzing and detecting abnormal traffic patterns, including sudden spikes in ICMP packets or other suspicious activities.
2.	Implement intrusion detection and prevention systems (IDS/IPS) to actively monitor network traffic for signs of potential DDoS attacks or other security threats.
3.	Establish incident response procedures to quickly identify and respond to security incidents, including DDoS attacks, to minimize their impact on network operations.
<br/> <br/>

<h2>Respond</h2>

In the event of a future cybersecurity incident, the following response plan should be implemented:<br /> <br />
1.	Immediately isolate affected systems or devices from the network to prevent further damage and contain the incident.
2.	Activate the incident response team to assess the situation, gather necessary data and information for analysis, and coordinate response efforts.
3.	Neutralize the attack by implementing appropriate countermeasures, such as blocking malicious traffic, deploying additional security controls, or leveraging cloud-based DDoS mitigation services.
4.	Conduct a thorough post-incident analysis to identify root causes, lessons learned, and areas for improvement in incident response procedures and network security measures.

<h2>Recover</h2>

To facilitate the recovery process and minimize downtime, the following steps should be taken:<br /> <br />
1.	Prioritize the restoration of critical network services and resources to ensure business continuity and minimize the impact on operations.
2.	Restore data and systems from backup copies to recover any lost or corrupted data caused by the DDoS attack.
3.	Implement measures to strengthen network resilience and improve incident response capabilities to better handle future cybersecurity incidents.

<h2>Reflection/Notes</h2>

•	The DDoS attack highlights the importance of implementing robust network security measures, including firewall configurations, access controls, and network monitoring tools, to mitigate the risk of similar incidents in the future.

•	Continuous monitoring, regular audits, and security awareness training are essential components of a proactive cybersecurity strategy to protect against evolving threats and vulnerabilities.

•	Incident response procedures should be regularly reviewed, updated, and tested to ensure they are effective in mitigating and responding to cybersecurity incidents promptly and effectively.


 <!--
 ```diff
- text in red
+ text in green
! text in orange
