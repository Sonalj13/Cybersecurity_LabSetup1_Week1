Week 1 — Cybersecurity Lab Setup

Objective

Set up a Kali Linux virtual machine in Oracle VirtualBox and verify its network connectivity.

Environment

- Virtualization software: Oracle VirtualBox
- Operating system: Kali Linux
- Network mode: NAT Network
- IPv4 address observed: "10.0.0.4/24"
- Default gateway observed: "10.0.0.1"

Setup and verification

1. Started the Kali Linux virtual machine.
2. Checked the IPv4 configuration using "ip -4 addr".
3. Checked the routing table using "ip route".
4. Tested DNS resolution and internet connectivity using "ping -c 4 google.com".
5. Saved screenshots of the VirtualBox network settings and terminal checks.

Results

The network commands completed successfully, and internet connectivity was verified.

Evidence

Add your screenshots to the repository and link them here:

- VirtualBox network settings
- Kali network configuration
- Network connectivity test

Outstanding work

- Confirm whether the instructor requires the specific IP address "10.0.0.2/24".
- Complete the Windows virtual machine setup if required by the instructor.
- Complete any remaining Week 1 tasks specified in the course instructions.

Troubleshooting notes

The Kali virtual machine initially used DHCP and received "10.0.0.4/24". The gateway was "10.0.0.1", and internet connectivity worked. The assigned address has not been changed to a static address.

Learning reflection

I learned how to inspect an IPv4 address, identify the default gateway, and test network connectivity from Kali Linux.
