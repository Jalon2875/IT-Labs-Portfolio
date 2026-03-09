# Active Directory Group Policy Lab

## Objective
Demonstrate how to create and apply a Group Policy Object (GPO) in Active Directory to restrict user access to the Control Panel.

This lab simulates a common enterprise IT scenario where administrators restrict system settings for standard users.

---

## Lab Environment

- Windows Server (Domain Controller)
- Windows Client Machine
- Active Directory Domain: helpdesk.local
- Virtualization: VirtualBox

---

## Tasks Performed

1. Installed and configured Active Directory Domain Services
2. Created Organizational Units (OUs)
3. Created domain users
4. Joined a workstation to the domain
5. Created a Group Policy Object
6. Linked the GPO to an Organizational Unit
7. Configured policy to disable Control Panel access
8. Forced Group Policy update using command line
9. Verified policy application with `gpresult`

---

## Commands Used
gpupdate /force
gpresult /r

---

## Verification

The Group Policy Object was successfully applied to the user account.

The command below confirmed the applied policy:
gpresult /r
