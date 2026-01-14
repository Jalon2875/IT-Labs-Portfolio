# Domain Join & Network Troubleshooting Lab

## Objective
Join a Windows 10 client machine to an Active Directory domain and troubleshoot common DNS and network connectivity issues.

## Lab Environment
- Oracle VirtualBox
- Windows Server 2019 (Domain Controller)
- Windows 10 (Help Desk Client)
- Active Directory Domain Services
- DNS
- Command Prompt

## Lab Steps

### 1. Domain Controller IP Configuration
Verified static IP configuration on the domain controller.
![Domain Controller IP Configuration](01-dc-ipconfig.png)

### 2. Client DNS Configuration
Configured the Windows 10 client to use the domain controller as its DNS server.
![Client DNS Configured](02-helpdesk-dns-configured.png)

### 3. Network Connectivity Test
Verified network connectivity between the client and domain controller using `ping`.
![Ping Domain Controller](03-ping-domain-controller.png)

### 4. Domain Join Success
Successfully joined the Windows 10 client to the Active Directory domain.
![Domain Join Success](04-domain-join-success.png)

### 5. Domain User Login
Confirmed domain functionality by logging in with a domain user account.
![Domain User Login](05-domain-user-login.png)

## What I Learned
- How DNS directly impacts Active Directory domain joins
- How to troubleshoot domain join failures
- How to configure client DNS for AD environments
- How domain authentication works in real environments
- Hands-on experience with Active Directory and Windows networking
