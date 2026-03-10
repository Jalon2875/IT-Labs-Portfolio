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
## Lab Walkthrough

### Step 1 – Open Group Policy Management
![Group Policy Management](1_gpo_management_console.png)

### Step 2 – Create Organizational Unit
![Create OU](2_create_ou.png)

### Step 3 – Create Test User
![Create Test User](3_create_test_user.png)

### Step 4 – Create Group Policy Object
![Create GPO](4_create_gpo.png)

### Step 5 – Configure Control Panel Restriction
![Configure Policy](5_configure_policy.png)

### Step 6 – Link GPO to OU
![Link GPO](6_link_gpo.png)

### Step 7 – Verify Policy with gpresult
![GPResult](7_gpresult_results.png)

### Step 8 – Confirm Policy Applied
![Policy Applied](8_gpo_policy_applied.png)

### Step 9 – Control Panel Blocked
![Control Panel Blocked](9_control_panel_blocked.png)

## Commands Used
gpupdate /force
gpresult /r

---

## Verification

The Group Policy Object was successfully applied to the user account.

The command below confirmed the applied policy:
gpresult /r
