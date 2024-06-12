NetworkMiner in a Nutshell

NetworkMiner is a versatile tool with multiple capabilities that make it useful for network forensics investigations. Below is a brief overview of its main features:
Capability	Description
Traffic sniffing	Intercepts, sniffs, and logs network packets.
Parsing PCAP files	Parses pcap files and details the contents of the packets.
Protocol analysis	Identifies protocols used within the parsed pcap files.
OS fingerprinting	Identifies operating systems by reading pcap files (using Satori and p0f).
File Extraction	Extracts images, HTML files, and emails from parsed pcap files.
Credential grabbing	Extracts credentials from parsed pcap files.
Clear text keyword parsing	Extracts cleartext keywords and strings from parsed pcap files.

Note: The Professional edition of NetworkMiner offers additional features not available in the free edition.
Operating Modes

NetworkMiner operates in two main modes:

    Sniffer Mode:
        Primarily available on Windows.
        Although it has sniffing capabilities, it's not as reliable as other dedicated sniffing tools like Wireshark or tcpdump.
        Recommended to use other tools for primary sniffing purposes.

    Packet Parsing/Processing:
        Parses traffic captures for a quick overview and essential information.
        Ideal for identifying "low-hanging fruit" before conducting a deeper investigation.

Pros and Cons

Pros:

    OS fingerprinting.
    Easy file extraction.
    Credential grabbing.
    Clear text keyword parsing.
    Provides an overall network overview.

Cons:

    Not suitable for active sniffing.
    Ineffective for large pcap investigations.
    Limited filtering options.
    Not designed for manual traffic investigation.

Differences Between Wireshark and NetworkMiner

NetworkMiner and Wireshark share some features but differ significantly in their use cases. Below is a comparison of their features:
Feature	NetworkMiner	Wireshark
Purpose	Quick overview, traffic mapping, and data extraction	In-depth analysis
GUI	✅	✅
Sniffing	✅ (not primary)	✅
Handling PCAPS	✅	✅
OS Fingerprinting	✅	❌
Parameter/Keyword Discovery	✅	Manual
Credential Discovery	✅	✅
File Extraction	✅	✅
Filtering Options	Limited	✅
Packet Decoding	Limited	✅
Protocol Analysis	❌	✅
Payload Analysis	❌	✅
Statistical Analysis	❌	✅
Cross-Platform Support	✅	✅
Host Categorisation	✅	❌
Ease of Management	✅	✅
Best Practices

    NetworkMiner is best used for a quick overview of the network, initial traffic mapping, and extracting essential data.
    Wireshark should be used for in-depth analysis and detailed investigation of network traffic.

By leveraging both tools appropriately, you can efficiently capture, analyze, and investigate network traffic to uncover malicious activities, security breaches, and other network-related issues.
