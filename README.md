# Virtualization-Home-Lab
A project documenting the set-up abd configuration of a virtualized Windows/Linux environment using Oracle VirtualBox

ENVIRONMENT AND TOOLS
Hypervisor: Oracle VM VirtualBox (Version 7.2.6)
Host OS: Windows 10/11 Home/Pro
Guest OS: Ubuntu Desktop 24.04 (Linux)
Hardware Allocated: 4GB RAM, 2 CPUs, 25GB Dynamic Storage.

STEP BY STEP IMPLEMENTATION
BIOS Configuration: Verified and enabled "Virtualization Technology" (Intel VT-x/AMD-V) in the system firmware.
Dependency Fix: Resolved a Microsoft Visual C++ 2019 error by manually installing the Redistributable package before running the VirtualBox installer.
VM Creation: Configured the virtual hardware and mounted the Ubuntu ISO as a virtual optical drive.
Network Setup: Set the Virtual Adapter to NAT (to provide internet access while keeping the VM isolated from my physical home network).

TROUBLESHOOTING
Problem: VirtualBox wouldn't install due to a C++ Redistributable error.
The Fix: Identified that VirtualBox 7.x requires the 2019+ library. Downloaded and installed the x64 version from Microsoft’s official site and performed a system reboot to clear the installer cache.

##LESSONS LEARNED
Learned how a Type 2 Hypervisor manages hardware resources.
Gained experience with Linux installation and disk partitioning.
Understood the importance of Dependencies in software deployment.'

WORK DOCUMENTATION
![VM3](https://github.com/user-attachments/assets/a6feb1f4-3a94-475f-b501-05e3148c4dc4)
![VM2](https://github.com/user-attachments/assets/4678d223-6b48-46d2-a7e3-cff02cba49ee)
![VM1](https://github.com/user-attachments/assets/4eae67af-8e9c-41f0-8fc9-613f54b7da59)
![vm4](https://github.com/user-attachments/assets/b2175b76-0a24-4b50-9c11-96c2ce4b3ba4)
