# Network Forensics

PCAP analysis and incident investigation write-ups focused on real-world malware campaigns and attack patterns.

## About

This repository documents my network forensics investigations using Wireshark. Each write-up follows a structured methodology: evidence identification, attack timeline reconstruction, IOC extraction, and conclusion with confidence levels.

Malware families analyzed include Emotet, TrickBot, IcedID, Formbook/XLoader, and others.

## Investigations

| # | Investigation | Malware | Key Findings |
|---|--------------|---------|-------------|
| 01 | [Emotet Two-Stage Delivery](./01-emotet-two-stage-delivery/) | Emotet | Two-stage payload delivery, dual C2 channels, public IP reconnaissance |

## Methodology

Every investigation follows the same structure:

- **Summary** — what happened, to whom, what was the impact
- **Environment** — victim details, network context, time window
- **IOCs** — consolidated table with type, context, and confidence level
- **Attack Timeline** — chronological sequence of events that advanced the attack
- **Conclusion** — attack narrative with causality, including what was and was not observed

## Tools

Wireshark, VirusTotal, MalwareBazaar, URLhaus

## Author

Gustavo Nunes — Cybersecurity student focused on defensive security and incident response.
- [LinkedIn](https://www.linkedin.com/in/gnunes-it1/)

)
