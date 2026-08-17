# Windows 11 IT Support Lab

## Project Overview

This project documents my hands-on Windows 11 IT support lab built using Oracle VirtualBox. The purpose of the lab was to practice common tasks performed by IT Support and Help Desk technicians, including operating system installation, local user administration, permissions, disk management, Windows updates, and troubleshooting.

## Lab Environment

- Oracle VirtualBox
- Windows 11 Pro
- Virtual Machine
- Local administrator and standard user accounts
- Windows Disk Management
- Device Manager
- Command Prompt
- Windows Update

## 1. Windows 11 Virtual Machine Setup

I created a Windows 11 virtual machine in Oracle VirtualBox and configured the required virtual hardware.

The VM configuration included:

- Windows 11 ISO
- 4 GB RAM
- 2 virtual processors
- 80 GB virtual hard disk
- Windows 11 Pro installation

### VM Configuration

![VM Creation](01-VM-Creation-Configuration.png)

![VM Hardware Configuration](02-VM-Hardware-Configuration.png)

![Virtual Hard Disk](03-Virtual-Hard-Disk-Configuration.png)

![VM Configuration Summary](04-VM-Configuration-Summary.png)

## 2. Windows 11 Installation

I installed Windows 11 Pro manually inside the virtual machine and completed the initial operating system configuration.

This included:

- Selecting Windows 11 Pro
- Completing Windows installation
- Configuring the device name
- Completing the initial Windows setup
- Verifying the Windows 11 installation

### Installation Process

![Windows 11 Installation](08-Windows11-Installation-Progress.png)

![Windows 11 Device Name](09-Windows11-Device-Name.png)

![Windows 11 Desktop](11-Windows11-Desktop.png)

![Windows 11 Pro Verification](12-Windows11-Pro-Verification.png)

## 3. Local User Account Administration

I practiced creating and managing local Windows user accounts.

I created separate accounts to simulate an IT support environment:

- **LabAdmin** – administrator account
- **TestUser** – standard user account

I verified the accounts through Windows account settings, the login screen, Local Users and Groups, and Command Prompt.

### User Account Verification

![Local User Created](13-Local-User-Created.png)

![User Login Screen](14-User-Account-Login-Screen.png)

![Administrator Command Prompt](15-Administrator-Command-Prompt.png)

## 4. User Permissions and UAC Testing

I tested the difference between administrator and standard-user permissions.

Tasks included:

- Reviewing local users and groups
- Checking group membership
- Verifying standard-user permissions
- Testing User Account Control (UAC)
- Confirming that administrator credentials are required for elevated administrative actions

This demonstrates the principle of least privilege commonly used in business IT environments.

![Standard User Permissions](28-Standard-User-Permissions-Verification.png)

![UAC Credential Prompt](29-UAC-Admin-Credential-Prompt.png)

## 5. Disk Management and Partitioning

I used Windows Disk Management to practice storage administration.

Tasks included:

- Accessing Disk Management
- Troubleshooting a Disk Management access issue
- Adding a second virtual disk
- Identifying unallocated disk space
- Creating and configuring a new volume
- Verifying the completed disk configuration

### Disk Management

![Disk Management Access Error](18-Disk-Management-Access-Error.png)

![Disk Management Restored](19-Disk-Management-Access-Restored.png)

![Second Virtual Disk](20-Second-Virtual-Disk-Configuration.png)

![Unallocated Disk](34-Disk-Unallocated-Space.png)

![New Volume Configuration](35-New-Volume-Configuration.png)

![Final Disk Configuration](36-Disk-Management-Final.png)

## 6. Windows Update

I used Windows Update to check for, download, and install operating system and security updates.

After completing the updates, I verified that the system reported that it was up to date.

![Windows Update In Progress](16-Windows-Update-In-Progress.png)

![Windows Update Completed](17-Windows-Update-Completed.png)

![Windows Update Up to Date](30-Windows-Update-Up-to-Date.png)

## 7. Device Manager Troubleshooting

During the lab, Device Manager showed a driver/device issue.

I investigated the issue and installed VirtualBox Guest Additions. After completing the troubleshooting process, I checked Device Manager again to verify the result.

This provided hands-on practice with identifying and resolving a common virtual-machine driver issue.

### Before Troubleshooting

![Device Manager Driver Error](31-Device-Manager-Driver-Error.png)

### After Troubleshooting

![Device Manager After Guest Additions](32-Device-Manager-After-Guest-Additions.png)

## 8. Final Verification

After completing the configuration and troubleshooting tasks, I verified that the Windows 11 virtual machine was operational.

![Windows 11 VM Running](37-Windows11-VM-Running.png)

## Troubleshooting Experience

During this project, I encountered issues rather than completing every task without errors. I used the problems as opportunities to practice troubleshooting.

Examples included:

- Disk Management access issues
- Device Manager driver/device issues
- Virtual machine resource configuration
- Windows update and configuration tasks

I worked through the issues by identifying the symptoms, checking system settings, making configuration changes, and verifying the results.

## Skills Demonstrated

- Windows 11 installation and configuration
- Oracle VirtualBox
- Virtual machine configuration
- Windows user account administration
- Local Users and Groups
- Administrator vs. standard-user permissions
- User Account Control (UAC)
- Command Prompt
- Windows Disk Management
- Disk and volume configuration
- Windows Update
- Device Manager
- Basic driver troubleshooting
- VirtualBox Guest Additions
- IT troubleshooting and documentation

## Project Outcome

This lab provided practical experience with Windows 11 administration and common IT support tasks. It strengthened my understanding of user management, permissions, operating system maintenance, storage management, virtualization, and troubleshooting in a Windows environment.
