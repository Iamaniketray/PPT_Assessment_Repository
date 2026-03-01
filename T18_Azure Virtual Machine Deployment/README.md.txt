# Azure Virtual Machine Deployment

## Project Overview
This project demonstrates launching and configuring a basic Azure Virtual Machine using the Azure Portal. It covers resource group creation, VM deployment, and remote access.

## Objective
- Create a Resource Group.
- Deploy an Azure Virtual Machine.
- Access the VM remotely and verify its running status.

## Steps
1. Log in to the Azure Portal.
2. Create a Resource Group:
   - Name: ppt-rg
3. Navigate to Virtual Machines → Create → Azure Virtual Machine.
4. Configure VM details:
   - VM Name: ppt-vm
   - Resource Group: ppt-rg
   - Image: Ubuntu Server or Windows Server
   - Size: Standard B1s (or default sandbox size)
   - Authentication: Username & Password or SSH Key
5. Click Review + Create → Create.
6. After deployment, verify VM Status: Running.
7. Access the VM:
   - For Ubuntu:
     ```bash
     ssh username@<public-ip>
     ```
   - For Windows:
     Use Remote Desktop (RDP) with public IP.
8. Confirm successful login.

## Proof
- Screenshot 1: Resource Group and VM creation.
- Screenshot 2: VM status showing Running.
- Screenshot 3: Successful remote access via CMD/SSH or RDP.

## Outcome
A successfully deployed and accessible Azure Virtual Machine demonstrating basic cloud compute provisioning.