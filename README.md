# # Lab 02 – Windows 10 Domain Join

## Objective
Join a Windows 10 client to the Active Directory domain and verify successful domain authentication.

## Environment
- Windows Server 2022 (Domain Controller)
- Windows 10 Pro
- VirtualBox
- Domain: solvexlab.local

## Configuration
- Configured Windows 10 network settings to use the domain DNS server
- Joined Windows 10 to the solvexlab.local domain
- Restarted client to complete domain join
- Verified computer object creation in Active Directory

## Validation
- Confirmed computer account appears in Active Directory Users and Computers
- Logged into Windows 10 using a domain user account
- Verified domain context using `whoami`
