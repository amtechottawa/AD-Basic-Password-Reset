# Active Directory - Password Reset
Changing a User's Password in Active Directory GUI

## Summary

This is a simple lab that demonstrates how to reset a user's forgotten password in Active Directory. No PowerShell commands but a visual demonstration of how to do it in the dashboard. This repository contains screenshots for each step to visualize what is happening.

## Environment

- Hypervisor: VMware
- OS: Windows Server 2025
- Server: AM-DC-01

## Prerequisites

- User must have Domain Admin or delegated permissions to reset passwords

## Steps

### 1. Go to the Server Manager

<p align="center">
  <img src="https://github.com/user-attachments/assets/38d2a7e2-46a4-4ba3-b338-843f682c7ac4" alt="Opening Server Manager from the Start menu" width="633">
</p>

### 2. Go to "Tools" and Then Click "Active Directory Users and Computers"

<p align="center">
  <img src="https://github.com/user-attachments/assets/c253d58f-3feb-4791-b3d5-262a3d411c66" alt="Tools menu in Server Manager" width="700">
</p>

### 3. From Active Directory Click on "Users"

<p align="center">
  <img src="https://github.com/user-attachments/assets/f92f468e-f9ec-45ee-a76a-4da41d077335" alt="Users container in Active Directory Users and Computers" width="700">
</p>

### 4. Find the User With the Password Issue and Right-Click to Reset Password

<p align="center">
  <img src="https://github.com/user-attachments/assets/4bcfee5a-e9af-4d9c-b246-c9826e3c8622" alt="Right-click menu with Reset Password option" width="700">
</p>

### 5. Enter New Password and Confirm

<p align="center">
  <img src="https://github.com/user-attachments/assets/077fc228-c55e-4a01-adfd-cfa9b9361794" alt="Reset Password dialog" width="700">
<

