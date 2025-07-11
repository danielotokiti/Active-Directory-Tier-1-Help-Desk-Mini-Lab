# Active-Directory-Tier-1-Help-Desk-Mini-Lab
Overview
Provisioned isolated Windows Server 2022 and Windows 10 environments on VirtualBox to emulate a small enterprise domain setup.  
Focused on foundational Tier 1 Help Desk tasks: user management, group assignments, OU structuring, and domain authentication.

---

## Tasks Completed
- Installed and configured Active Directory Domain Services (AD DS) and DNS on Windows Server 2022.
- Promoted server to Domain Controller for `homelab.local` and validated AD replication and DNS health.
- Created Organizational Units (OUs) to logically group users and resources.
- Set up security groups to manage access and applied basic membership structures.
- Added domain user accounts (e.g. `daniel.otokiti`), set unique password policies, and tested password resets.
- Configured a Windows 10 endpoint to join the domain, ensuring it resolved DNS queries via the domain controller.
- Performed typical Tier 1 admin tasks:
  - Password resets
  - Unlocking locked accounts
  - Testing different login formats (`homelab\username` vs `username@homelab.local`).

---

## Screenshots
- Active Directory Users & Computers showing OUs and users.
- Group properties with members listed.
- Windows 10 login using domain credentials.
- Successful `nslookup` to resolve `homelab.local`.
- Admin Tasks
