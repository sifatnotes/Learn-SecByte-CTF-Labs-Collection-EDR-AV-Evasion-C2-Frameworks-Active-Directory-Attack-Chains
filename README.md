# Learn-SecByte-CTF-Labs-Collection-EDR-AV-Evasion-C2-Frameworks-Active-Directory-Attack-Chains
Learn SecByte CTF Labs Collection | EDR/AV Evasion, C2 Frameworks &amp; Active Directory Attack Chains
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on EDR/AV defense evasion, Living off the Land binaries and scripts (LOLBins/LOLScripts), command & control (C2) framework operations (Sliver, Havoc, Mythic), payload generation and delivery, credential access, post-exploitation persistence, network pivoting, and Active Directory attack chains designed for cybersecurity students, CTF players, red team operators, penetration testers, and threat hunters.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Surviving in modern enterprise environments requires bypassing Endpoint Detection and Response (EDR) agents, blending in with legitimate administrative tools, operating stealthy C2 channels, and executing multi-stage Active Directory attack chains. Hosted on [Learn SecByte](https://learn.secbyte.org/), this defense evasion and offensive operations collection provides advanced, hands-on technical training.

From bypassing AV signatures and hooks, abusing dual-use binaries (Certutil, MSBuild, PowerShell), and deploying modern open-source C2 frameworks (Sliver, Havoc, Mythic), to dumping host credentials, establishing covert persistence across Windows and Linux, pivoting through multi-homed networks, and abusing Kerberos delegation to compromise Active Directory domains, these labs build production-grade offensive tradecraft.

---

## Lab Collection & Index

Below is the complete, searchable index of all EDR/AV evasion, C2 framework, persistence, credential access, and Active Directory challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **EDR & AV Evasion: Understand, Observe, Defend** | Defense Evasion & EDR Bypass | Userland API unhooking, direct/indirect syscalls (`Hell's Gate`), AMSI/ETW patching, memory allocation protection | [Access Lab](https://learn.secbyte.org/ctf/edr-av-evasion-understand-observe-defend) |
| 2 | **Living Off The Land: LOLBins & LOLScripts** | Defense Evasion & EDR Bypass | Living off the Land Binaries/Scripts (`Certutil`, `MSBuild`, `InstallUtil`, `PowerShell`), proxy execution, signature bypass | [Access Lab](https://learn.secbyte.org/ctf/living-off-the-land-lolbins-lolscripts) |
| 3 | **Pivoting and Multi-Network Operations** | Pivoting & Lateral Movement | Multi-tier network pivoting, SOCKS proxy routing, Chisel, Ligolo-ng, SSH port forwarding, internal subnet discovery | [Access Lab](https://learn.secbyte.org/ctf/pivoting-and-multi-network-operations) |
| 4 | **Lateral Movement: From Initial Foothold to Internal Reach** | Pivoting & Lateral Movement | PsExec, WMI/WinRM execution, Pass-the-Hash (PtH), Pass-the-Ticket (PtT), SSH agent hijacking | [Access Lab](https://learn.secbyte.org/ctf/lateral-movement-from-initial-foothold-to-internal-reach) |
| 5 | **Kerberos Attacks and Delegation Abuse** | Active Directory & Credentials | Kerberoasting, AS-REP Roasting, Unconstrained/Constrained/Resource-Based Constrained Delegation (RBCD) abuse | [Access Lab](https://learn.secbyte.org/ctf/kerberos-attacks-and-delegation-abuse) |
| 6 | **Active Directory Attack Chains: From Misconfigurations to Domain** | Active Directory & Credentials | Enterprise AD attack paths, BloodHound graph analysis, ACL/ACE exploitation, AD CS abuse, DCSync | [Access Lab](https://learn.secbyte.org/ctf/active-directory-attack-chains-from-misconfigurations-to-dom) |
| 7 | **Defense Evasion Fundamentals** | Defense Evasion & EDR Bypass | Code obfuscation, string encryption, sandbox detection/sleep evasion, payload staging, anti-analysis | [Access Lab](https://learn.secbyte.org/ctf/defense-evasion-fundamentals) |
| 8 | **Linux Persistence Techniques: From Hidden Startup Hooks to DE** | Persistence & Host Operations | Systemd service backdoors, cron jobs, SSH authorized keys, PAM module backdoors, shell profile hooks | [Access Lab](https://learn.secbyte.org/ctf/linux-persistence-techniques-from-hidden-startup-hooks-to-de) |
| 9 | **Windows Persistence Techniques: Detect, Defend, Verify** | Persistence & Host Operations | Windows Registry Run keys, Scheduled Tasks, WMI event subscriptions, service creation, DLL hijacking | [Access Lab](https://learn.secbyte.org/ctf/windows-persistence-techniques-detect-defend-verify) |
| 10 | **Credential Access Techniques** | Active Directory & Credentials | LSASS memory dumping, SAM/SYSTEM registry extraction, DPAPI blob decryption, browser credential harvesting | [Access Lab](https://learn.secbyte.org/ctf/credential-access-techniques) |
| 11 | **Command and Control Frameworks: Sliver, Havoc, Mythic** | C2 Operations & Delivery | C2 deployment (Sliver, Havoc, Mythic), listener configuration, malleable C2 profiles, agent generation, tasking | [Access Lab](https://learn.secbyte.org/ctf/command-and-control-frameworks-sliver-havoc-mythic) |
| 12 | **Payload Generation and Delivery Techniques** | C2 Operations & Delivery | Shellcode generation, custom encoders, HTML smuggling, Office macro delivery, ISO/LNK payload staging | [Access Lab](https://learn.secbyte.org/ctf/payload-generation-and-delivery-techniques) |

---

## Categories

### 1. Defense Evasion, LOLBins & EDR Bypass
Master techniques to bypass static/dynamic AV signatures, patch telemetry hooks (AMSI/ETW), and leverage native system binaries (LOLBins) for stealth execution.
- [Defense Evasion Fundamentals](https://learn.secbyte.org/ctf/defense-evasion-fundamentals)
- [Living Off The Land: LOLBins & LOLScripts](https://learn.secbyte.org/ctf/living-off-the-land-lolbins-lolscripts)
- [EDR & AV Evasion: Understand, Observe, Defend](https://learn.secbyte.org/ctf/edr-av-evasion-understand-observe-defend)

### 2. C2 Operations, Payload Generation & Delivery
Generate custom obfuscated payloads, set up stealthy delivery mechanisms, and operate modern command and control frameworks.
- [Payload Generation and Delivery Techniques](https://learn.secbyte.org/ctf/payload-generation-and-delivery-techniques)
- [Command and Control Frameworks: Sliver, Havoc, Mythic](https://learn.secbyte.org/ctf/command-and-control-frameworks-sliver-havoc-mythic)

### 3. Active Directory, Kerberos & Credential Access
Extract credentials from memory and registry stores, abuse Kerberos delegation protocols, and chain Active Directory misconfigurations to achieve Domain Admin.
- [Credential Access Techniques](https://learn.secbyte.org/ctf/credential-access-techniques)
- [Kerberos Attacks and Delegation Abuse](https://learn.secbyte.org/ctf/kerberos-attacks-and-delegation-abuse)
- [Active Directory Attack Chains: From Misconfigurations to Domain](https://learn.secbyte.org/ctf/active-directory-attack-chains-from-misconfigurations-to-dom)

### 4. Pivoting, Lateral Movement & Host Persistence
Tunnel traffic across isolated corporate subnets, execute lateral movement primitives, and maintain persistent access on compromised Windows and Linux systems.
- [Pivoting and Multi-Network Operations](https://learn.secbyte.org/ctf/pivoting-and-multi-network-operations)
- [Lateral Movement: From Initial Foothold to Internal Reach](https://learn.secbyte.org/ctf/lateral-movement-from-initial-foothold-to-internal-reach)
- [Windows Persistence Techniques: Detect, Defend, Verify](https://learn.secbyte.org/ctf/windows-persistence-techniques-detect-defend-verify)
- [Linux Persistence Techniques: From Hidden Startup Hooks to DE](https://learn.secbyte.org/ctf/linux-persistence-techniques-from-hidden-startup-hooks-to-de)

---

## Learning Path

Follow this structured progression path to build end-to-end expertise in modern red team operations, defense evasion, and domain dominance:

1. **Phase 1: Payload Generation, Delivery & EDR Evasion** — Develop evasive payloads, bypass AV/EDR hooks, and utilize LOLBins:
   - [Defense Evasion Fundamentals](https://learn.secbyte.org/ctf/defense-evasion-fundamentals)
   - [Payload Generation and Delivery Techniques](https://learn.secbyte.org/ctf/payload-generation-and-delivery-techniques)
   - [Living Off The Land: LOLBins & LOLScripts](https://learn.secbyte.org/ctf/living-off-the-land-lolbins-lolscripts)
   - [EDR & AV Evasion: Understand, Observe, Defend](https://learn.secbyte.org/ctf/edr-av-evasion-understand-observe-defend)

2. **Phase 2: Command & Control Operations & Host Persistence** — Operate C2 implants and establish stealthy persistence on target OS hosts:
   - [Command and Control Frameworks: Sliver, Havoc, Mythic](https://learn.secbyte.org/ctf/command-and-control-frameworks-sliver-havoc-mythic)
   - [Windows Persistence Techniques: Detect, Defend, Verify](https://learn.secbyte.org/ctf/windows-persistence-techniques-detect-defend-verify)
   - [Linux Persistence Techniques: From Hidden Startup Hooks to DE](https://learn.secbyte.org/ctf/linux-persistence-techniques-from-hidden-startup-hooks-to-de)

3. **Phase 3: Credential Access, Pivoting & Lateral Movement** — Dump host credentials, pivot across network subnets, and move laterally:
   - [Credential Access Techniques](https://learn.secbyte.org/ctf/credential-access-techniques)
   - [Pivoting and Multi-Network Operations](https://learn.secbyte.org/ctf/pivoting-and-multi-network-operations)
   - [Lateral Movement: From Initial Foothold to Internal Reach](https://learn.secbyte.org/ctf/lateral-movement-from-initial-foothold-to-internal-reach)

4. **Phase 4: Active Directory Attack Chains & Domain Takeover** — Exploit Kerberos delegation and execute multi-stage Active Directory domain compromises:
   - [Kerberos Attacks and Delegation Abuse](https://learn.secbyte.org/ctf/kerberos-attacks-and-delegation-abuse)
   - [Active Directory Attack Chains: From Misconfigurations to Domain](https://learn.secbyte.org/ctf/active-directory-attack-chains-from-misconfigurations-to-dom)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and target environment specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy red team tools (Sliver C2, Havoc C2, Mythic, Impacket, Mimikatz, BloodHound, Chisel, Ligolo-ng) inside an isolated security workstation.
4. Generate obfuscated payloads, bypass EDR controls, harvest credentials, pivot across segmented networks, compromise Active Directory controllers, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute defense evasion scripts, C2 frameworks, or Active Directory exploitation tools against unauthorized networks, production systems, or third-party infrastructure.
