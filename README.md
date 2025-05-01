# Malware Testing Resources [Educational Use Only]

> **DISCLAIMER:** This repository is intended for **educational and research purposes only**. Do not use malware or tools in any unauthorized environment. Always test in isolated, virtualized labs. The creator is not responsible for any misuse.

---

## Table of Contents

- [About](#about)
- [Malware Sample Repositories](#malware-sample-repositories)
- [Malware Analysis Sandboxes](#malware-analysis-sandboxes)
- [Online Scanners & Tools](#online-scanners--tools)
- [Educational GitHub Repositories](#educational-github-repositories)
- [Useful Tools for Analysis](#useful-tools-for-analysis)
- [Recommended Courses & Labs](#recommended-courses--labs)
- [Best Practices](#best-practices)
- [License](#license)
- [Contributing](#contributing)

---

## About

This repository contains a list of the best and safest platforms for downloading, testing, and analyzing malware in controlled environments. It is useful for:

- Cybersecurity students
- Malware analysts
- Reverse engineers
- Threat researchers

---

## Malware Sample Repositories

| Source | Description |
|--------|-------------|
| [MalwareBazaar](https://bazaar.abuse.ch/) | Public malware sample database by abuse.ch |
| [VX Underground](https://www.vx-underground.org/) | One of the largest malware and research archives |
| [TheZoo](https://github.com/ytisf/theZoo) | GitHub repo of real malware binaries |
| [MalShare](https://malshare.com/) | Community-driven malware repository |
| [Triage Samples](https://tria.ge/samples) | Malware samples from Hatching Triage |
| [AVCaesar](https://avcaesar.malware.lu/) | Malware repository by CERT Malware.lu |
| [Das Malwerk](https://dasmalwerk.eu/) | Malware samples released weekly |

---

## Malware Analysis Sandboxes

| Tool | Notes |
|------|-------|
| [Any.Run](https://any.run/) | Real-time, interactive sandbox |
| [Hybrid Analysis](https://www.hybrid-analysis.com/) | Rich, detailed behavior reports |
| [CAPE Sandbox](https://cape.contextis.com/) | Fork of Cuckoo, supports config extraction |
| [Triage](https://tria.ge/) | Advanced sandbox with actor attribution |
| [Joe Sandbox](https://www.joesandbox.com/) | High-fidelity analysis (limited free tier) |
| [Cuckoo Sandbox](https://github.com/cuckoosandbox/cuckoo) | Open-source malware sandboxing system |

---

## Online Scanners & Tools

| Tool | Function |
|------|----------|
| [VirusTotal](https://www.virustotal.com/) | Multi-AV scanner and behavioral analysis |
| [Unpac.me](https://www.unpac.me/) | Unpacks packed or obfuscated binaries |
| [ThreatExpert](http://www.threatexpert.com/) | Archived behavioral analysis reports |
| [ReversingLabs](https://www.reversinglabs.com/) | Deep static and threat analysis |
| [InQuest Labs](https://labs.inquest.net/) | Static file dissection and hunting |
| [MetaDefender](https://metadefender.opswat.com/) | Secure file scanning and sanitization |
| [Intezer Analyze](https://analyze.intezer.com/) | Code reuse detection and analysis |

---

## Educational GitHub Repositories

| Repo | Description |
|------|-------------|
| [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) | Curated list of tools, papers, and sandboxes |
| [TheZoo](https://github.com/ytisf/theZoo) | Malware binaries for education |
| [Cuckoo Sandbox](https://github.com/cuckoosandbox/cuckoo) | Malware sandboxing system |
| [IDA Free Scripts](https://github.com/techbliss/ida-free-script) | Python tools for IDA Free |
| [Malware Techniques](https://github.com/0xRick/malware-techniques) | Modern malware techniques & evasion |
| [Reverse Engineering Tools](https://github.com/cugu/awesome-forensics) | Tools for memory & file analysis |

---

## Useful Tools for Analysis

- **Process Monitor (ProcMon)** – Real-time file, registry, process monitoring
- **Wireshark** – Packet capturing and analysis
- **x64dbg** – Open-source debugger
- **PEStudio** – Static binary inspection
- **Sysmon** – Logs detailed system activity
- **IDA Free / Ghidra / Binary Ninja** – Disassemblers and reverse engineering
- **ApateDNS / INetSim** – Simulate DNS & internet services

---

## Recommended Courses & Labs

| Resource | Notes |
|---------|-------|
| [Malware Unicorn RE101](https://malwareunicorn.org/workshops/re101.html) | Beginner-friendly reversing course |
| [Practical Malware Analysis](https://www.nostarch.com/malware) | Classic textbook with labs |
| [Honeynet Challenges](https://www.honeynet.org/challenges/) | Real-world reverse engineering tasks |
| [Open Security Training](https://opensecuritytraining.info/) | Free RE & exploitation courses |
| [CyberDefenders Labs](https://cyberdefenders.org/labs/) | Free labs on malware, DFIR, and more |

---

## Best Practices

- Always analyze samples in **isolated environments** (VMs, no host sharing).
- Use **snapshots** before running any malware.
- Disable network access unless necessary and controlled.
- Log everything: process creation, registry access, file writes.
- Never share samples carelessly—label clearly and store safely.

---

## License

MIT License. This repo provides references only; please review and respect each linked platform’s terms.

---

## Contributing

Got more sources or tools? Feel free to open a pull request or file an issue.

---