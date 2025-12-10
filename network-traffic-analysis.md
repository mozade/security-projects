# Network Traffic Analysis & Threat Detection

Comprehensive analysis of enterprise-like PCAP datasets using Security Onion and Wireshark to identify suspicious network activity, detect anomalies, and map potential attacker behavior. The investigation focused on protocol misuse, abnormal outbound connections, and patterns consistent with command-and-control (C2) communication.

Objectives

Inspect PCAP files to identify abnormal or unauthorized traffic flows.

Detect indicators of malicious activity, including DNS tunneling, HTTP misuse, and C2 beacons.

Correlate alerts and logs generated within Security Onion.

Map suspicious sessions to attacker techniques and potential compromise paths.

Produce actionable findings for SOC triage and threat hunting workflows.

Methodology
1. Initial Traffic Inspection

Loaded PCAPs into Wireshark and Security Onion.

Applied protocol-based filters (DNS, HTTP, TCP anomalies).

Examined session metadata including TTL values, unusual ports, and irregular packet sizes.

2. Suspicious Pattern Identification

Detected abnormal outbound traffic originating from internal hosts.

Flagged repeated beacon-like intervals consistent with automated malware communication.

Identified mismatched protocol behavior (e.g., HTTP traffic without valid headers).

3. Correlation With Security Onion Alerts

Cross-referenced network sessions with IDS/IPS alerts generated in Security Onion.

Mapped Snort/Suricata signatures to observed activity.

Validated findings by correlating timestamps, source/destination pairs, and anomaly scores.

Tools & Techniques

Wireshark for packet-level inspection

Security Onion for IDS/IPS alerts and session correlation

Protocol analysis (DNS, HTTP, TCP anomaly detection)

Threat hunting methodologies (frequency analysis, beacon detection, endpoint correlation)

Key Findings

Detected abnormal outbound connections from compromised hosts.

Identified repeated periodic traffic patterns suggestive of C2 beaconing.

Observed protocol misuse consistent with data exfiltration attempts.

Mapped suspicious sessions to attacker activity detectable via IOC-based and behavior-based methods.

Summary

The analysis revealed multiple indicators consistent with early-stage malware communication and lateral movement activity. Correlating Wireshark findings with IDS/IPS alerts provided a clear understanding of the threat behavior and produced actionable insights for SOC detection engineering and network monitoring enhancements.

This is an academic network investigation. All sensitive details and sample indicators have been removed.
