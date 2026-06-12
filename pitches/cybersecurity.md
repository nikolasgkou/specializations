# 🔐 Cybersecurity
**Specialization branch · Zone01 Athens**

> This branch explores offensive security through hands-on practice across ten solo projects: you build penetration-testing and reconnaissance tooling, reverse-engineer binaries and live malware, and find and exploit web and system vulnerabilities inside isolated virtual machines, always for authorized, ethical use.

## The branch in numbers
| | |
|---|---|
| Format | 10 projects (no piscine) |
| Projects | 10 (10 solo · 0 team) |
| Core stack | Linux & Windows VMs, binary exploitation, reverse engineering, web security (OWASP), cryptography |

## What you'll build
- A penetration-testing toolkit performing port scanning, directory brute-forcing, network mapping, and HTTP header analysis, in the style of Nmap and Dirsearch.
- A program that analyzes a live Windows malware sample in a VM, kills it, removes its persistence, and recovers the attacker's IP.
- A controlled ransomware simulation with a matching encryptor, decryptor, a unique per-victim ransom note, and antivirus-evasion techniques in an isolated Windows VM.
- An OWASP Juice Shop attack exploiting five-plus Top 10 flaws, SQLi, XSS, IDOR and CSRF, with full remediation recommendations.

## The journey
| # | Project | What you build | Solo/Team |
|---|---|---|---|
| 1 | pentest-kit | Toolkit: port scanner, dir brute-forcer, header analyzer | Solo |
| 2 | osint-master | OSINT recon tool from IPs, usernames, domains | Solo |
| 3 | image-inspector | Image forensics: EXIF plus steganography LSB extraction | Solo |
| 4 | defuse | Analyze Windows malware in a VM; build eradicator | Solo |
| 5 | escalator | Enumerate and root a vulnerable Linux VM | Solo |
| 6 | hole-in-bin | Reverse-engineer and exploit binaries via buffer overflows | Solo |
| 7 | vuln-hunter | Exploit five-plus OWASP Top 10 flaws in Juice Shop | Solo |
| 8 | hidden-bytes | Binary-evasion and polymorphic tools with reverse-shell payload | Solo |
| 9 | merge | Binder merging two executables into one binary | Solo |
| 10 | ransomware-lab | Ransomware simulation: encryptor, decryptor, ransom note | Solo |

## You'll learn
- Network scanning, enumeration, and passive OSINT reconnaissance techniques
- Reverse engineering binaries and assembly-level memory-corruption exploitation
- Live malware analysis, persistence removal, and eradication in VMs
- Web exploitation across the OWASP Top 10 vulnerabilities
- Image forensics: EXIF metadata extraction and steganography recovery
- File encryption, cryptography, crypters, and antivirus-evasion techniques

## It's a great fit if…
- You like thinking like an attacker to build stronger, better-informed defenses across systems and networks.
- You enjoy low-level work: assembly, binary formats, memory corruption, and reverse engineering executables from scratch.
- You are comfortable setting up and operating inside isolated Linux and Windows virtual machines for offensive testing.
- You enjoy explaining technical findings and remediation steps to stakeholders in a consultant or audit role.

---

## References & further reading
New to some of these tools? These are the official docs and starting points for the technologies used in this branch. All techniques here are for authorized, ethical use only.

- **Nmap** — port scanning and network mapping. [nmap.org/book](https://nmap.org/book/)
- **dirsearch** — web directory brute-forcing. [github.com/maurosoria/dirsearch](https://github.com/maurosoria/dirsearch)
- **OWASP Top 10** — the core web vulnerability list. [owasp.org/Top10](https://owasp.org/www-project-top-ten/)
- **OWASP Juice Shop** — the deliberately vulnerable practice app. [owasp.org/juice-shop](https://owasp.org/www-project-juice-shop/)
- **Ghidra** — reverse engineering and disassembly. [github.com/NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)
- **GDB** — the GNU debugger for stepping through and inspecting binaries. [sourceware.org/gdb](https://sourceware.org/gdb/documentation/)
- **Radare2** — open-source reverse-engineering framework and disassembler. [rada.re](https://rada.re/n/)
- **ExifTool** — reading image metadata for forensics. [exiftool.org](https://exiftool.org/)
- **VirtualBox** — isolated Linux/Windows lab VMs. [virtualbox.org/manual](https://www.virtualbox.org/manual/)
