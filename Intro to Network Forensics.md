**Introduction to Network Forensics**

Network Forensics is a crucial subdomain within the broader field of digital forensics. It centers on investigating network traffic to gather evidence and understand potential problems. The goal is to record network packets and create investigatable sources, ultimately establishing a root-cause analysis of an event. This helps in detecting malicious activities, security breaches, policy/regulation compliance, system health, and user behavior.
Key Investigation Questions (5W):

    Who: Identifies the source IP and port.
    What: Examines the data or payload.
    Where: Specifies the destination IP and port.
    When: Records the time and date.
    Why: Understands how and what happened.

Systematic evidence capture and timeline creation are critical for successful network forensics investigations.
Network Forensics Use Cases

    Network Discovery: Identifying connected devices, rogue hosts, and network load.
    Packet Reassembly: Investigating traffic flow by reconstructing packet sequences, useful in unencrypted traffic.
    Data Leakage Detection: Monitoring packet transfer rates to identify potential data leaks.
    Anomaly and Malicious Activity Detection: Reviewing network load, ports, and addresses to detect malicious activities and vulnerabilities.
    Policy/Regulation Compliance Control: Ensuring network behavior adheres to policies and regulations.

Advantages of Network Forensics

    Network-Based Evidence: Easier to capture than logs and IOCs.
    Minimal Noise: Sniffing doesn't create significant noise or alerts.
    Resilience of Evidence: Network traffic, unlike logs, is harder to destroy.
    Log Availability: Logs provide valuable information to support investigations.
    Detection of Non-Residential Threats: Network traffic analysis can detect memory-resident and non-residential malicious activities.

Challenges of Network Forensics

    Deciding the Approach: Determining the focus of the investigation (e.g., SOC, IH/IR, Threat Hunting).
    Sufficient Data Collection: Ensuring comprehensive data capture without gaps.
    Short Data Capture Windows: Continuous full-packet capture is resource-intensive.
    Encrypted Traffic: Difficult to analyze but still provides metadata for hypotheses.
    Privacy Concerns: Compliance with regulations like GDPR.
    Nonstandard Port Usage: Attackers may use unconventional ports to evade detection.
    Time Zone Issues: Ensuring consistent time zone usage in multi-region investigations.
    Lack of Logs: Logs are often erased by attackers to hinder investigations.

Sources of Network Forensics Evidence

Evidence can be gathered from various sources:

    TAPS
    InLine Devices
    SPAN Ports
    Hubs, Switches, Routers
    DHCP Servers
    Name Servers
    Authentication Servers
    Firewalls, Web Proxies
    Central Log Servers
    Logs (IDS/IPS, Application, OS, Device)

Primary Purposes of Network Forensics

    Security Operations (SOC): Daily monitoring of system performance, user behavior, and security issues.
    Incident Handling/Response and Threat Hunting: Investigating incidents to detect malicious activity and understand data flow content.

Investigated Data Types in Network Forensics

    Live Traffic
    Traffic Captures: Full packet captures and network flows.
    Log Files

NetworkMiner is a powerful tool for processing and analyzing live and captured traffic, aiding in network forensic investigations by providing a clear view of network activities and potential threats.
