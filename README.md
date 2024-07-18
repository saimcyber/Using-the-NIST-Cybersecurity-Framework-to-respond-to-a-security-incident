# Project Summary: Improving Network Security Using the NIST Cybersecurity Framework (CSF)

## Background
Our multimedia company, offering web design services, graphic design, and social media marketing solutions to small businesses, recently experienced a Distributed Denial of Service (DDoS) attack. The attack, which lasted two hours, was executed through a flood of ICMP packets that compromised our internal network. The incident highlighted a critical vulnerability in our firewall configuration.

## Incident Response and Immediate Actions
During the attack, the incident management team took immediate steps to mitigate the impact:

- Blocked incoming ICMP packets to stop the attack.
- Shutdown non-critical network services to preserve resources.
- Restored critical network services to maintain business operations.

Post-incident investigation revealed that the attack exploited an unconfigured firewall, allowing the malicious actor to overwhelm our network with ICMP pings.

## Implemented Measures
Following the incident, our network security team implemented several measures to prevent future attacks:

- **Firewall rule to limit ICMP packets:** We configured the firewall to limit the rate of incoming ICMP packets.
- **Source IP address verification:** The firewall was updated to check for spoofed IP addresses on incoming ICMP packets.
- **Network monitoring software:** We deployed monitoring software to detect abnormal traffic patterns.
- **Intrusion Detection/Prevention System (IDS/IPS):** Implemented an IDS/IPS system to filter ICMP traffic based on suspicious characteristics.

## NIST Cybersecurity Framework Integration
To further enhance our network security, we developed a comprehensive plan based on the NIST Cybersecurity Framework (CSF). The plan includes the following steps:

### Identify
- Conduct regular audits of internal networks, systems, devices, and access privileges.
- Identify potential security gaps and vulnerabilities.

### Protect
- Implement policies, procedures, training, and tools to mitigate cybersecurity threats.
- Strengthen firewall configurations and access controls.

### Detect
- Enhance monitoring capabilities to detect potential security incidents more quickly.
- Deploy advanced threat detection tools to identify suspicious activities.

### Respond
- Develop response strategies to contain, neutralize, and analyze security incidents.
- Implement process improvements based on post-incident analyses.

### Recover
- Establish protocols to restore affected systems and data to normal operation.
- Ensure business continuity and data recovery plans are in place and regularly tested.
