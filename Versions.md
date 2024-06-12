Version Differences

NetworkMiner has seen significant improvements and changes across its versions, particularly between versions 1.6 and 2.7. Below are the key differences and enhancements:
Mac Address Processing

Version 2.0 and Later:

    Feature: MAC address-specific correlation.
    Benefit: Helps identify MAC address conflicts.
    Availability: This feature is not available in versions prior to 2.0.

Example:
Sent/Received Packet Processing

Version 1.6 and Earlier:

    Feature: Detailed sent/received packet processing.
    Benefit: Provides a more detailed investigation of sent and received packets.
    Availability: This feature is not available in versions after 1.6.

Example:
Frame Processing

Version 1.6 and Earlier:

    Feature: Frame processing.
    Benefit: Provides the number of frames and essential details about them.
    Availability: This feature is not available in versions after 1.6.

Example:
Parameter Processing

Version 2.0 and Later:

    Feature: Extensive parameter handling.
    Benefit: Captures a wider range of parameters compared to earlier versions.
    Availability: Version 1.6.x captures fewer parameters than version 2.0 and later.

Example:
Cleartext Processing

Version 1.6 and Earlier:

    Feature: Cleartext data processing.
    Benefit: Provides all extracted cleartext data in a single tab, useful for investigating cleartext data within traffic.
    Limitation: Cannot match cleartext data to specific packets.
    Availability: This feature is not available in versions after 1.6.

Example:
Summary of Feature Differences
Feature	Version 1.6 and Earlier	Version 2.0 and Later
Mac Address Processing	❌	✅
Sent/Received Packet Processing	✅	❌
Frame Processing	✅	❌
Parameter Processing	Limited	Extensive
Cleartext Processing	✅	❌
Conclusion

NetworkMiner's evolution from version 1.6 to version 2.7 has seen the introduction of new features and the removal of some older ones. Version 2.7 brings enhancements like MAC address correlation and improved parameter handling, while version 1.6 offers detailed packet and frame processing. Understanding these differences is crucial for leveraging the tool effectively in various network forensics scenarios.
