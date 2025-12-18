# Objective
  - the purpose of this lab was to install and configure two virtual machines, Windows and kali linux using Oracle VirtualBox. This lab is being used as a foundation virtualized enviornment for future security and networking testing while gaining knowledge and hands on experience with OS installation, virtual machine configuration, and basic network setup

## Tools used
  - Oracle VirtualBox
  - Windows 10 ISO
  - Kali Linux ISO
  - Host system (Windows 10)

## Network Configuration
  - Virtual Machines were configured using NAT networking to allow internet access while remaining isolated from the host network
  - Windows NAT config [here](https://github.com/Mayala115/Windows-Kali-Homelab/blob/main/Snapshot/Windows-NAT.PNG)

## VM Setup

 - Windows 10 VM
    1. Created new VM in VirtualBox
    2. assigned:
      - 4 CPU Cores
      - 4 GB RAM
      - 50 GB Dynamically allocated storage
    3. Attached Windows 10 ISO
    4. Windows Installation Completed
    5. verified Internet connectivity [here](https://github.com/Mayala115/Windows-Kali-Homelab/blob/main/Snapshot/winINT.png)
    6. Snapshot of Windows Running in VM [here](https://github.com/Mayala115/Windows-Kali-Homelab/blob/main/Snapshot/winHome.png)

  - Kali Linux VM
      1. Created new VM in VirtualBox
      2. Assigned
         - 4 CPU Cores
         - 4 GB RAM
         - 50 GB Dyanamically allocated storage
      3. Attached Kali Linux ISO
      4. Kali Linux Installation Completed
      5. Verified Interner connnectivity
    
## Validation and Testing

  -FILL-LATER

## Challenges and Troubleshooting
  - Windows 10 did not boot properly.
      - Resolved by changeing the location of the ISO file on the host system
   
# What I Learned
  - How to configure and deploy multiple operating system in a virtual enviornment
  - Resource allocation is important in the performance of the VM
  - NAT networking provides internet access while maintaining isolation

# Future Changes
  - 
