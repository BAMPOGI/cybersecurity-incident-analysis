# cybersecurity-incident-analysis
An analysis of a fictional DDoS ICMP flood incident, demonstrating the practical application of the NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).

# Incident Report Analysis: DDoS ICMP Flood
Applying the NIST Cybersecurity Framework to a fictional network disruption scenario.

## Executive Summary
The company experienced a security incident when all network services unexpectedly became unresponsive. The cybersecurity team determined that the disruption was caused by a Distributed Denial of Service (DDoS) attack involving a flood of ICMP packets. In response, the team blocked the malicious traffic and temporarily disabled non-essential network services to ensure that critical services could be restored.

---

## NIST Cybersecurity Framework Analysis

| Function | Action Taken |
| :--- | :--- |
| **Identify** | Determined a malicious actor flooded the network with ICMP packets (ICMP flood attack). Identified the need to restore critical services to normal function. |
| **Protect** | Implemented a new firewall rule to limit the rate of incoming ICMP packets. Deployed an IDS/IPS system to filter traffic based on suspicious characteristics. |
| **Detect** | Configured source IP address verification on the firewall to check for spoofed IPs. Implemented network monitoring software to detect abnormal traffic patterns. |
| **Respond** | Isolated affected systems and devices. Analyzed and monitored network logs for continued suspicious activity while restoring critical services. |
| **Recover** | Restored network services to a normal functioning state. Verified that the new firewall rules effectively block suspicious ICMP packets. |

---

## Reflections & Key Takeaways
This project allowed me to practice the structural application of the NIST Cybersecurity Framework to a specific network disruption. By analyzing a DDoS attack, I learned how to balance immediate mitigation with long-term detection strategies.

* **Defense in Depth:** While blocking traffic was the immediate response, implementing IDS/IPS filtering and source IP verification provides a multi-layered defense.
* **Operational Continuity:** The primary goal during the 'Identify' phase is ensuring critical services return to normal function as quickly as possible.
* **Proactive Monitoring:** Network monitoring software is essential for detecting abnormal traffic patterns before they escalate into a total service outage.
* **Policy Refinement:** The 'Recover' phase involves updating firewall rules to ensure the network is more resilient than it was before the attack.

> **Note:** This is a fictional scenario created for educational purposes to demonstrate proficiency in incident response and the NIST Framework.
