# NMAP Cheat Sheet

**nmap -sP <10.10.0.0/16>** == Ping scan against network

**nmap -sC -sV <TARGET> -oA <OUTPUT>** == syn scan with version and default script
  
**nmap -A -iL <hosts> -T4** == os detection, version, script (-A) against hosts list (-iL), fast (-T4)
  
Target syntax :
- 192.168.0.0/24
- 192.168.0-4.0-10
- 192.168.1.1 192.168.1.110
  
Port syntax :
- -p 22,80,443
- -p 0-1024
- -p- == all ports
  
Output file :
- -oX == to xml file
- -oG == to grep file
- -oA == to every format
