# Pentest/HackTheBox build playbook for Kali Linux VM on M1 (ARM64)
First of all, this Ansible playbook was inspired by IppSec's  <a href="https://github.com/IppSec/parrot-build">parrot-build</a>.
It contains the tools and configurations I personally use when Pentesting/HacktheBoxing and sometimes bughunting.
Please feel free to reach out should you find any issues.

## Installation
1. Install ansible via pip3
```
pip3 install ansible
```

2. Clone this repository
3. Run the playbook with sudo token
```
sudo whoami
ansible-playbook playbook.yml
```

## List of tools
- anew
- assetfinder
- BurpSuite Community
- chisel (ARM and x64) 
- cookie quick manager
- dirsearch
- ffuf  
- foxyproxy
- gf 
- ghidra
- go  
- httprobe 
- impacket
- jwtcrack
- linpeas
- meg 
- pspy
- smbmap
- subfinder 
- ublock  
- VSCode
- wappalyzer
