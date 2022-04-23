---
cover: >-
  https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=2970&q=80
coverY: 0
---

# Port Scan

{% hint style="info" %}
**Good to know:** A better approach involves sending a different kinds of packets to a system to try ask for any kind of answer to determine if system is alive or not.
{% endhint %}

**Port Scanning Options**

| `nmap -F [target]`                             | Perform a fast scan            |
| ---------------------------------------------- | ------------------------------ |
| `nmap -p [port(s)] [target]`                   | Scan specific ports            |
| `nmap -p [port name(s)] [target]`              | Scan ports by name             |
| `nmap -sU -sT -p U:[ports],T:[ports] [target]` | Scan ports by protocol         |
| `nmap -p 1-65535 [target]`                     | Scan all ports                 |
| `nmap --top-ports [number] [target]`           | Scan top ports                 |
| `nmap -r [target]`                             | Perform a sequential port scan |
| `nmap -O --osscan-guess [target]`              | Attempt to guess an unknown OS |
| `nmap -sV [target]`                            | Service version detection      |
| `nmap -sV --version-trace [target]`            | Troubleshooting version scans  |
| `nmap -sR [target]`                            | Perform a RPC scan             |
