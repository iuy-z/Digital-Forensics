# **Digital Forensics Tasks Overview**  

## **1. Examining a Forensic Image with Autopsy**  
Utilizing **Autopsy** to analyze a forensic disk image, extract deleted files, examine file system metadata, and reconstruct user activities. This involves inspecting logs, user accounts, and timestamps to identify anomalies.  

## **2. Network Forensics using Wireshark**  
Capturing and analyzing **network traffic** with **Wireshark** to detect suspicious activities such as **unauthorized data transfers, malware communications, and unusual protocol usage**. Packet inspection helps identify threats and reconstruct attack patterns.  

## **3. Rhino Hunt with Autopsy**  
Investigating a **forensic case study** involving hidden files and metadata manipulation using **Autopsy**. The goal is to uncover evidence related to user activity, file access history, and system modifications.  

## **4. Rhino Hunt with Wireshark**  
Analyzing **network packets** related to a forensic case using **Wireshark** to track **suspicious IP addresses, DNS queries, and encrypted command-and-control (C2) traffic** used for malicious activities.  

## **5. Memory Analysis with Autopsy**  
Extracting and analyzing **RAM dumps** using **Autopsy** to retrieve running processes, detect in-memory malware execution, and identify system artifacts that disappear after a reboot.  

## **6. Memory Forensics of LastPass and Keeper**  
Performing **memory forensics** to analyze password manager applications (**LastPass, Keeper**), identifying sensitive data stored in memory, including **user credentials, session tokens, and encryption keys**.  

## **7. Capturing and Examining the Registry**  
Extracting and examining **Windows Registry hives (SAM, SYSTEM, SOFTWARE)** to uncover evidence of **user activity, USB device connections, installed applications, malware persistence, and system modifications**.  

## **8. Examining a Windows Disk Image**  
Forensic analysis of a **Windows disk image** to retrieve deleted files, inspect system logs, recover browser history, and identify traces of malicious activity using **Autopsy and FTK Imager**.  

## **9. Email Forensics**  
Investigating **email headers, attachments, and message metadata** to detect phishing emails, spoofed addresses, malware-laden attachments, and social engineering attempts. **Email header analysis** is used to trace the sender’s IP and email routing.  

## **10. Android Studio Emulator**  
Setting up and configuring **Android Studio’s Emulator** to simulate **real-world Android environments** for forensic testing, mobile malware analysis, and application behavior monitoring.  

## **11. Rooting Android Studio's Emulator**  
Gaining **root access** to the Android emulator to bypass system restrictions and perform **deep forensic investigations**, such as extracting **hidden logs, SMS messages, app data, and system configurations**.  

## **12. Forensic Acquisition from Android**  
Extracting forensic data from an **Android device** using tools like **ADB (Android Debug Bridge), Autopsy, and Magnet AXIOM** to retrieve **call logs, messages, app data, and deleted files** for forensic analysis.  

## **13. Android Analysis with Autopsy**  
Using **Autopsy** to analyze an Android device’s file system, retrieve **deleted SMS, call logs, browsing history**, and inspect **log files for evidence of tampering or malware infections**.  

## **14. Making a Rooted Android Emulator**  
Building a **custom rooted Android emulator** for forensic research and malware analysis, allowing unrestricted access to **system partitions, hidden files, and app permissions**.  

## **15. iPhone Analysis with Autopsy**  
Performing **iOS forensics** using **Autopsy** to extract data from an **iPhone backup**, analyze app logs, recover deleted messages, and investigate **iCloud sync artifacts**.  

## **16. Windows and Linux Machines**  
Investigating **Windows and Linux systems** by analyzing **event logs, system processes, network configurations, and user activity logs** to detect unauthorized access or malware infections.  

## **17. Velociraptor Server on Linux**  
Deploying **Velociraptor**, an open-source **endpoint monitoring and forensic analysis tool**, on a **Linux server** for real-time system monitoring and incident response.  

## **18. Investigating a PUP with Velociraptor**  
Using **Velociraptor** to analyze **Potentially Unwanted Programs (PUPs)**, identifying hidden installations, tracking execution behavior, and detecting unauthorized system modifications.  

## **19. Investigating a Bot with Velociraptor**  
Detecting and analyzing a **bot infection** using **Velociraptor**, identifying **malicious process injections, C2 server communications, and automated scripts** running on a compromised system.  

## **20. Investigating a Two-Stage RAT with Velociraptor**  
Tracking a **Remote Access Trojan (RAT)** using **Velociraptor**, analyzing its **multi-stage execution**, persistence mechanisms, and data exfiltration techniques to understand the attack chain.  
Tools Used for Digital Forensics Tasks
Below are the primary tools used across different forensic investigations:

1. General Forensic Analysis Tools
🔹 Autopsy – Open-source digital forensics platform for disk image analysis, file recovery, and timeline analysis.
🔹 FTK Imager – Disk imaging and data recovery tool used for Windows forensic analysis.
🔹 Velociraptor – Endpoint monitoring and incident response tool for analyzing system activity and malware infections.
🔹 RegRipper – Extracts and analyzes Windows registry hives for user activity, malware persistence, and system modifications.

2. Network Forensics Tools
🔹 Wireshark – Packet capture and network traffic analysis tool for investigating suspicious connections, malware activity, and C2 communications.
🔹 NetworkMiner – Network forensic analysis tool for extracting artifacts from packet captures (PCAP).

3. Memory & Live System Forensics Tools
🔹 Volatility Framework – Memory forensics tool for extracting running processes, hidden malware, and system artifacts from RAM dumps.
🔹 Memdump & DumpIt – Used for capturing system memory for forensic analysis.
🔹 Windows Sysinternals (Process Explorer, Autoruns, etc.) – Identifies malicious processes, startup programs, and system modifications.

4. Disk & File System Forensics Tools
🔹 Magnet AXIOM – Commercial forensic suite for examining mobile and desktop artifacts.
🔹 ExifTool – Metadata extraction tool for analyzing images, documents, and embedded timestamps.
🔹 Bulk Extractor – Extracts email addresses, credit card numbers, and other digital evidence from raw disk images.

5. Email & Web Forensics Tools
🔹 MailXaminer – Email forensic tool for analyzing headers, attachments, and email metadata.
🔹 Google Admin Toolbox Message Header Analyzer – Investigates email routing and sender authentication.




