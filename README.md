# helpdesk-home-lab

# IT Helpdesk Home Lab

Virtualised Windows domain built to practise tier-1 helpdesk tasks.

## Environment
- Hypervisor: VirtualBox
- Server: Windows Server 2016 (AD DS, DNS, DHCP)
- Clients: Windows 10, domain-joined

## Labs Completed

### 1. Active Directory User Management
Created OUs and users, reset passwords, unlocked accounts.
![AD Users](screenshots/01-active-directory/users.png)

**Scenario:** User locked out after failed logins → unlocked account in ADUC,
reset password with "must change at next logon", verified login on client.

### 2. Group Policy
Configured mapped drives and a password policy for the Staff OU.
![GPO](screenshots/02-group-policy/mapped-drive.png)

## What I Learned
- How domain authentication and account lockout work
- Troubleshooting a client that won't join the domain (DNS pointed to wrong server)
