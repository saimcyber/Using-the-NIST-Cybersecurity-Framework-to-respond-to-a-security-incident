# Using-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Network Security Improvement Plan</title>
</head>
<body>
    <h1>Project Summary: Improving Network Security Using the NIST Cybersecurity Framework (CSF)</h1>

    <h2>Background</h2>
    <p>Our multimedia company, offering web design services, graphic design, and social media marketing solutions to small businesses, recently experienced a Distributed Denial of Service (DDoS) attack. The attack, which lasted two hours, was executed through a flood of ICMP packets that compromised our internal network. The incident highlighted a critical vulnerability in our firewall configuration.</p>

    <h2>Incident Response and Immediate Actions</h2>
    <p>During the attack, the incident management team took immediate steps to mitigate the impact:</p>
    <ul>
        <li>Blocked incoming ICMP packets to stop the attack.</li>
        <li>Shutdown non-critical network services to preserve resources.</li>
        <li>Restored critical network services to maintain business operations.</li>
    </ul>
    <p>Post-incident investigation revealed that the attack exploited an unconfigured firewall, allowing the malicious actor to overwhelm our network with ICMP pings.</p>

    <h2>Implemented Measures</h2>
    <p>Following the incident, our network security team implemented several measures to prevent future attacks:</p>
    <ul>
        <li><strong>Firewall rule to limit ICMP packets:</strong> We configured the firewall to limit the rate of incoming ICMP packets.</li>
        <li><strong>Source IP address verification:</strong> The firewall was updated to check for spoofed IP addresses on incoming ICMP packets.</li>
        <li><strong>Network monitoring software:</strong> We deployed monitoring software to detect abnormal traffic patterns.</li>
        <li><strong>Intrusion Detection/Prevention System (IDS/IPS):</strong> Implemented an IDS/IPS system to filter ICMP traffic based on suspicious characteristics.</li>
    </ul>

    <h2>NIST Cybersecurity Framework Integration</h2>
    <p>To further enhance our network security, we developed a comprehensive plan based on the NIST Cybersecurity Framework (CSF). The plan includes the following steps:</p>

    <h3>Identify</h3>
    <ul>
        <li>Conduct regular audits of internal networks, systems, devices, and access privileges.</li>
        <li>Identify potential security gaps and vulnerabilities.</li>
    </ul>

    <h3>Protect</h3>
    <ul>
        <li>Implement policies, procedures, training, and tools to mitigate cybersecurity threats.</li>
        <li>Strengthen firewall configurations and access controls.</li>
    </ul>

    <h3>Detect</h3>
    <ul>
        <li>Enhance monitoring capabilities to detect potential security incidents more quickly.</li>
        <li>Deploy advanced threat detection tools to identify suspicious activities.</li>
    </ul>

    <h3>Respond</h3>
    <ul>
        <li>Develop response strategies to contain, neutralize, and analyze security incidents.</li>
        <li>Implement process improvements based on post-incident analyses.</li>
    </ul>

    <h3>Recover</h3>
    <ul>
        <li>Establish protocols to restore affected systems and data to normal operation.</li>
        <li>Ensure business continuity and data recovery plans are in place and regularly tested.</li>
    </ul>

</body>
</html>
