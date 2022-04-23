---
cover: >-
  https://images.unsplash.com/photo-1552664730-d307ca884978?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=2970&q=80
coverY: 0
---

# Basic Scans

**Quick reference for Nmap Security Scanner**

****

**Basic Scanning Techniques**

**Basic Scanning Techniques**

| `nmap [target]`                           | Scan a single target           |
| ----------------------------------------- | ------------------------------ |
| `nmap [target1, target2, etc]`            | Scan multiple targets          |
| `nmap -iL [list.txt]`                     | Scan a list of targets         |
| `nmap [range of IP addresses]`            | Scan a range of hosts          |
| `nmap [ip address/cdir]`                  | Scan an entire subnet          |
| `nmap -iR [number]`                       | Scan random hosts              |
| `nmap [targets] --exclude [targets]`      | Excluding targets from a scan  |
| `nmap [targets] --excludefile [list.txt]` | Excluding targets using a list |
| `nmap -A [target]`                        | Perform an agressive scan      |
| `nmap -6 [target]`                        | Scan an IPv6 target            |
