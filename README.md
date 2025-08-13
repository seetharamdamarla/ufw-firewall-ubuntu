# UFW Firewall on Ubuntu 22.04 

This task involved hands-on experience with **UFW (Uncomplicated Firewall)** on Ubuntu 22.04 — learning how to allow/block ports and test real-world traffic filtering.

---

## Task Objectives
- Configure a basic firewall on Linux using UFW
- Block inbound traffic on port **23 (Telnet)**
- Allow secure access via port **22 (SSH)**
- Test the firewall using Telnet
- Clean up rules and restore original settings

---

## Commands Summary

Full list: [ufw_commands_task4.txt]

## Highlights:
``` bash
sudo ufw enable
sudo ufw status numbered
sudo ufw deny 23
telnet localhost 23
sudo ufw allow 22
sudo ufw delete 23
```

## Screenshots
- Visual proof of each step is available in the screenshots/ folder.

## What I Learned

- How to manage firewall rules using UFW
- The importance of blocking insecure services (like Telnet)
- Real-world testing using Telnet
- Resetting and cleaning up firewall configurations
- Prepared for common firewall-related interview questions.

## Tools Used

- Ubuntu 22.04 LTS
- UFW (Uncomplicated Firewall)
- Terminal and Screenshot utility
- Telnet for connection testing

## Conclusion
This task provided valuable hands-on experience in configuring and managing firewalls using UFW on a Linux system. By blocking insecure ports like Telnet and allowing essential services such as SSH, I gained a practical understanding of how firewalls help secure a system from unauthorized access. From enabling UFW to testing real-world connections and cleaning up rules, this exercise strengthened both my technical skills and cybersecurity awareness.

