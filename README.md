# IT Help Desk Home Lab

A hands-on home lab built to demonstrate core IT help desk skills including Active Directory administration, ticketing system management, and PowerShell scripting.

## Lab Environment
- **Hypervisor:** Microsoft Hyper-V (Windows 11 Pro)
- **Domain Controller:** Windows Server 2022
- **Domain:** fernlab.local
- **Ticketing System:** osTicket v1.18.3

## Skills Demonstrated

### Active Directory
- Created Organizational Units (IT, HR, Finance, Helpdesk)
- Created and managed user accounts
- Performed password resets
- Disabled and enabled user accounts
- Unlocked locked-out accounts
- Configured Group Policy Objects (GPO)

### Ticketing System (osTicket)
- Installed and configured osTicket on local server
- Created and managed tickets through full lifecycle (Open → Resolved)
- Documented troubleshooting steps and resolutions

### PowerShell Scripting
- `Get-ADUsers.ps1` — Queries all AD users and displays account status
- `Reset-ADPassword.ps1` — Resets user password and unlocks account
- `Get-LockedAccounts.ps1` — Scans domain for locked out accounts

## Screenshots
Screenshots of all lab activities are included.
