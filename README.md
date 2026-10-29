# NETWORKWALKS-WEEK1-ZULFA-CYBERSECURITY-LAB-SETUP
week 1 cybersecurity lab

#  PROJECT OVERVIEW

For Week 1 of the Cybersecurity Internship held by Networkwalks, I was required to set up a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux.

I completed the lab setup by installing the required software, configuring a private NAT Network, establishing internet connectivity in Kali Linux, enabling shared resources between the host system and the virtual machine, and creating a virtual machine snapshot.

This lab provides a controlled environment for practicing cybersecurity concepts, exploring security tools, and performing authorized security testing. It also serves as a foundation for future practical exercises in network security and penetration testing.


# OBJECTIVES OF LAB

The main objective of this lab is to establish a functional virtual environment for learning and practicing cybersecurity concepts using Oracle VirtualBox and Kali Linux.

The specific objectives are to:

- Install and configure Oracle VirtualBox.
- Set up Kali Linux as the primary cybersecurity testing machine.
- Configure a private NAT Network using the 10.0.0.0/24 subnet.
- Establish internet connectivity within the Kali Linux virtual machine.
- Enable shared clipboard, drag-and-drop, and shared folder features.
- Create a virtual machine snapshot to preserve the lab configuration.
- Prepare the lab environment for future cybersecurity exercises and authorized penetration testing.

# THE PURPOSE OF LAB
The purpose of this lab is to gain practical experience in virtualization, Linux operating systems, network configuration, and cybersecurity testing using Oracle VirtualBox and Kali Linux.

This lab provides a controlled environment for exploring cybersecurity tools, practicing network scanning, performing reconnaissance, and learning vulnerability assessment techniques.

It also helps build a strong foundation for understanding how virtual machines communicate over a private network and how cybersecurity testing can be conducted safely and responsibly.

The lab will support future practical exercises by allowing additional virtual machines to be added as targets for authorized security testing.


# LAB SETUP PROCEDURE

 Step-1: Install 7-Zip

I installed 7-Zip to prepare for handling compressed files required during the lab setup.

![image alt](https://github.com/Zumashe/NETWORKWALKS-WEEK1-ZULFA-CYBERSECURITY-LAB-SETUP/blob/main/7-zip.png?raw=true)



 Step-2: Install Oracle VirtualBox

I installed Oracle VirtualBox on my Windows computer to create and manage the virtual machine for my cybersecurity lab.
![image_alt](https://github.com/Zumashe/NETWORKWALKS-WEEK1-ZULFA-CYBERSECURITY-LAB-SETUP/blob/main/oracle%20virtual%20box.png?raw=true)


 Step-3: Create a NAT Network

I created a NAT Network named CyberLab in VirtualBox and configured the network subnet to 10.0.0.0/24.

![image_alt](https://github.com/Zumashe/NETWORKWALKS-WEEK1-ZULFA-CYBERSECURITY-LAB-SETUP/blob/main/Natnetwork.png?raw=true)



Step-4: Download and Import Kali Linux

I downloaded and imported the Kali Linux virtual machine into Oracle VirtualBox to use it as my primary cybersecurity testing machine.

![image_alt](https://github.com/Zumashe/NETWORKWALKS-WEEK1-ZULFA-CYBERSECURITY-LAB-SETUP/blob/main/kali%20linux.png?raw=true)

Step-5: Configure Kali Linux IP Address

I configured the Kali Linux network settings according to the lab requirements, using the IP address "10.0.0.2/24".
![image_alt]()

Step-6: Configure Virtual Machine Settings

I enabled Shared Clipboard and Drag and Drop in VirtualBox. I also configured the shared folder using the host computer's "/downloads" folder as required.

![image_alt]()
![image_alt]()
![image_alt]()
![image_alt]()

Step-7: Configure Internet Connectivity

I configured and verified internet connectivity in Kali Linux to ensure that the virtual machine could access the internet as required.

![image_alt]()

 Step-8: Create a Virtual Machine Snapshot

After completing the lab configuration, I created a snapshot of my Kali Linux virtual machine to preserve the configured environment for future use.

![image_alt]()
# LAB VERFICATION

After completing the lab setup, I verified the main components of my cybersecurity lab according to the Networkwalks Week 1 instructions.

 Step-1: Verify VirtualBox and Kali Linux

I checked that Oracle VirtualBox was installed and that my Kali Linux virtual machine was available in VirtualBox Manager.

 Step-2: Verify NAT Network Configuration

I checked the VirtualBox network settings to confirm that the NAT Network was configured using the required subnet, `10.0.0.0/24`.

 Step-3: Verify Kali Linux IP Configuration

I checked the Kali Linux network configuration to confirm that the IP address was set according to the lab requirements: `10.0.0.2/24`.

 Step-4: Verify Internet Connectivity

I checked the internet connectivity of my Kali Linux virtual machine to confirm that it had internet access as required by the lab instructions.

 Step-5: Verify Virtual Machine Settings

I checked that Shared Clipboard, file Drag'n'Drop, and the shared folder were configured according to the lab requirements.

Step-6: Verify Virtual Machine Snapshot

I checked VirtualBox Manager to confirm that I had created a snapshot of my configured Kali Linux virtual machine.

 Verification Summary

I completed the required Phase 1 lab setup, including the Kali Linux configuration, network setup, internet connectivity, VirtualBox settings, and virtual machine snapshot.



#  PROBLEMS ENCOUNTERED AND SOLUTION

 Problem: Kali Linux Internet Connectivity

Problem: 
During the lab setup, I encountered an internet connectivity issue in my Kali Linux virtual machine, which prevented it from accessing the internet as required.

Solution:  
I checked the NAT Network configuration and Kali Linux network settings. Following the troubleshooting instructions provided by Networkwalks, I applied the recommended network connection commands and restarted the connection. After troubleshooting, I restored internet connectivity and verified that Kali Linux could access the internet.



# SECURITY AND ETHICAL USE

This laboratory is intended strictly for educational purposes only. All activities conducted within this environment are meant to support cybersecurity learning and ethical hacking practice.



# TOOLS AND RESOURCES

7-Zip:https://7-zip.org/download.html
VirtualBox: https://virtualbox.org/wiki/Downloads
Kali Linux: https://kali.org/get-kali
