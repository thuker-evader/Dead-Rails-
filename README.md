<p align="center">
  <img src="https://i.imgur.com/v7VkgA9.png" width="200" alt="Hazard Mask Logo"/>
</p>

<h1 align="center">Welcome to the Malware Testing Lab</h1>

> **Hello tester!**  
> If youve came here, you're probably curious about how malware works or maybe you're gearing up to tear apart some binaries in a virtual machine. Either way: **respect**. Just know this isn’t for the faint hearted. We're diving into the underworld of code.

---

## ⚠️ Before We Begin...

Let me be real with you: this stuff is dangerous. You’re going to be poking actual malware.

**This repo is ONLY for:**
- Students
- Security researchers
- Reverse engineers
- Ethical hackers

Please, **don’t be that person** who runs ransomware on their main laptop.  
**Use a VM. Take snapshots. Isolate your network. Be smart.**

---

## So, What’s This Repo About?

I’ve collected the best tools, sites, and sandboxes that real malware analysts use every day. No fluff, no shady links just the essentials to:
- Download real malware samples
- Analyze them in a safe lab
- Learn techniques used in the wild
- Level up your skills without burning down your system

---

## Where to Get Malware (Safely)

| Site | What’s Inside |
|------|----------------|
| [MalwareBazaar](https://bazaar.abuse.ch/) | Giant library of tagged malware |
| [VX Underground](https://www.vx-underground.org/) | Archive of real-world malware & research |
| [TheZoo](https://github.com/ytisf/theZoo) | GitHub repo full of live malware samples |
| [MalShare](https://malshare.com/) | Community-driven malware archive |
| [Das Malwerk](https://dasmalwerk.eu/) | Weekly releases with metadata |
| [Triage Samples](https://tria.ge/samples) | Download directly from sandbox reports |

---

## “I Want to See It Run!” — Use These Sandboxes

| Sandbox | Why It’s Awesome |
|---------|------------------|
| [Any.Run](https://any.run/) | Interactive, real-time malware sandbox |
| [Hybrid Analysis](https://www.hybrid-analysis.com/) | Detailed behavior reports + AV scores |
| [Joe Sandbox](https://www.joesandbox.com/) | Crazy detailed analysis (even evasive malware) |
| [CAPE Sandbox](https://cape.contextis.com/) | Great for extracting configs and behavior |
| [Cuckoo](https://github.com/cuckoosandbox/cuckoo) | Run your own analysis locally |

---

## Online Tools That Make You Look Smart

| Tool | What It Does |
|------|---------------|
| [VirusTotal](https://www.virustotal.com/) | Upload a file, get verdicts from 70+ AV engines |
| [Unpac.me](https://www.unpac.me/) | Unpacks obfuscated or packed malware |
| [Intezer Analyze](https://analyze.intezer.com/) | Finds code reuse in malware families |
| [InQuest Labs](https://labs.inquest.net/) | File dissection and threat hunting |
| [MetaDefender](https://metadefender.opswat.com/) | Secure multi-AV file scanning |

---

## GitHub Projects You’ll Want to Fork

- [Awesome Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) – Ultimate malware tools list
- [Malware Techniques](https://github.com/0xRick/malware-techniques) – Modern tactics used by malware
- [IDA Free Scripts](https://github.com/techbliss/ida-free-script) – Scripts to boost your RE workflow
- [Cuckoo Sandbox](https://github.com/cuckoosandbox/cuckoo) – Analyze malware in your own lab
- [TheZoo](https://github.com/ytisf/theZoo) – Yes, again—it’s just that useful

---

## Tools of the Trade

Here’s your malware analyst toolbox. Don’t leave home without it:

- **Wireshark** – For catching malware’s network chatter  
- **x64dbg** – Lightweight, powerful debugger  
- **Ghidra / IDA Free** – Disassemble like a boss  
- **ProcMon / ProcExp** – Watch the malware live  
- **Sysmon + ELK** – Deep event tracking  
- **PEStudio** – Quick insights into suspicious files  
- **ApateDNS / INetSim** – Fake the internet for malware

---

## Want to Learn? Start Here.

| Resource | Why It Rocks |
|----------|--------------|
| [Malware Unicorn RE101](https://malwareunicorn.org/workshops/re101.html) | The perfect intro to reverse engineering |
| [Practical Malware Analysis (Book)](https://www.nostarch.com/malware) | A classic, comes with hands-on labs |
| [CyberDefenders Labs](https://cyberdefenders.org/labs/) | Practice challenges for DFIR and malware |
| [OpenSecurityTraining](https://opensecuritytraining.info/) | Free courses on RE, assembly, exploitation |

---

## Pro Tips (From Someone Who Broke Their Host Machine Once...)

- **Run malware only in isolated virtual machines.**
- **Use snapshots** — one click, you're back in time.
- **No internet unless needed** — or use fake DNS/emulators.
- Label files clearly: `DO_NOT_EXECUTE_ON_HOST.exe`
- Monitor everything. Logs > guesswork.

---

## License

MIT License.  
All links and resources belong to their respective creators. This repo is just the guide to help you get started safely and responsibly.

---

## Wanna Contribute?

Spotted a broken link? Got a new sandbox to share? Open a pull request or file an issue. Sharing knowledge keeps this field alive.

---

**Stay safe. Stay curious. Don’t burn your system down.**