
```sh
 ██╗    ██╗██╗  ██╗███████╗████████╗███████╗████████╗ ██████╗ ███╗   ██╗███████╗
 ██║    ██║██║  ██║██╔════╝╚══██╔══╝██╔════╝╚══██╔══╝██╔═══██╗████╗  ██║██╔════╝
 ██║ █╗ ██║███████║█████╗     ██║   ███████╗   ██║   ██║   ██║██╔██╗ ██║█████╗  
 ██║███╗██║██╔══██║██╔══╝     ██║   ╚════██║   ██║   ██║   ██║██║╚██╗██║██╔══╝  
 ╚███╔███╔╝██║  ██║███████╗   ██║   ███████║   ██║   ╚██████╔╝██║ ╚████║███████╗
  ╚══╝╚══╝ ╚═╝  ╚═╝╚══════╝   ╚═╝   ╚══════╝   ╚═╝    ╚═════╝ ╚═╝  ╚═══╝╚══════╝
```

Ansible playbook to prep, harden, and personalize a fresh Kali install.

Usage:
------

- [Install Kali](https://www.kali.org/get-kali/)
- Clone this repo and run the deploy script:
    ```zsh
    git clone https://github.com/zyenai/whetstone
    cd whetstone
    sudo chmod +x deploy.sh
    ./deploy.sh
    ```
Notes:
------
This playbook configures [ufw](https://wiki.ubuntu.com/UncomplicatedFirewall) to block all incoming traffic. Two ufw profiles are included in `files/ufw/applications.d`. If you're not catching your shell, check ufw.  

Tools:
-------

- ansible-core
- asyncua
- awscli
- BAC0
- bacpypes
- bettercap
- bloodhound
- bokeh
- capstone
- cmake
- cpppo
- ctmodbus
- ctserial
- cython
- dnsmasq
- docker.io
- docker-compose
- donut-shellcode
- evil-winrm
- eyewitness
- gdb
- gdbserver
- ghidra
- gobuster
- golang
- gufw
- hcxtools
- htop
- jq
- kali-linux-default
- libgcrypt-dev
- libpcap-dev
- libreoffice
- libssl-dev
- mitm6
- mosh
- nbtscan-unixwiz
- ncat
- neo4j
- net-tools
- nfs-kernel-server
- opcua-client
- openjdk-11-jdk
- pandas
- parallel
- paramiko
- patator
- payloadsallthethings
- PEASS-ng suite
- pipenv
- poetry
- powershell
- pspy
- pwntools
- pycomm3
- pycrypto
- pylogix
- pymodbus
- pypykatz
- pyserial
- python3-dev
- python3-pip
- python-is-python3
- python-libpcap
- python-snap7
- pyusb
- realtek-rtl88xxau-dkms
- remmina
- requests
- rlwrap
- roadrecon
- ropper
- scite
- seclists
- stringio
- sysinternals
- testssl.sh
- tmux
- ufw
- unicorn
- winrm
- winrm-fs
- wireguard
- xclip
- xsel

Credits
-------

Original author: [@iesplin](https://github.com/iesplin/ansible-playbook-kali)

Remix by: [@illiterateTechpriest](https://github.com/illiterateTechpriest/)

License
-------

MIT
