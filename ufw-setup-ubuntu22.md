# Firewall Configuration Using UFW on Ubuntu 22.04

## Commands Used:

1) Enable UFW Firewall
``` bash
   sudo ufw enable
```
2) Check Current UFW Status and Rules
``` bash
    sudo ufw status numbered
```
3) Block Incoming Traffic on Port 23 (Telnet)
``` bash
    sudo ufw deny 23
```
4) Check Rules After Adding the Block
``` bash
   sudo ufw status numbered
```
5) Install Telnet (for Testing) 
``` bash
    sudo apt install telnet
```
6) Test Connection to Port 23
``` bash
    telnet localhost 23
```

7) Allow SSH Port (Optional but Recommended)
``` bash
     sudo ufw allow 22
```
8) Delete the Deny Rule on Port 23 (Clean-up) 
``` bash
    sudo ufw delete deny 23
```

9) Final Check of UFW Rules
``` bash
    sudo ufw status numbered
```

Notes:
- UFW (Uncomplicated Firewall) is a simplified frontend for managing iptables.
- Port 23 (Telnet) is blocked as it's insecure and should not be exposed to the internet.
- Port 22 (SSH) is allowed to ensure remote access remains functional.  based on the content give me a nice file name
