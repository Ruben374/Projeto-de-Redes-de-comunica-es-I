# Communications Networks Project - 2024/2025  

This project was developed as part of the **Communications Networks** course and serves as an assessment of the practical component. It focuses on designing and enabling communication between two networks: **Calendar Inc.** and **Horoscope Inc.**, two companies producing digital content for different market segments.  

The implementation was carried out using **GNS3**, configuring IP addressing, routing, NAT/PAT, VLANs, and network services.  

## 📌 Project Objectives  

- Establish inter-network communication between Calendar Inc. and Horoscope Inc.  
- Assign IPv4 and IPv6 addresses based on specific rules.  
- Configure static routing and default routes for full connectivity.  
- Implement **NAT/PAT** to allow Internet access, with exceptions for VLAN8 and VLAN18.  
- Deploy DHCP services for automatic IP assignment.  
- Set up web services and a client-server application for interactive communication.  

## 🏗️ Network Configuration  

## 🚀 Project Phases  

### **📍 Phase 1: IP Addressing (Report by 15/11/2024)**  
- Define network and broadcast addresses.  
- Identify IP ranges for all devices.  
- Determine NAT/PAT address ranges.  
- Assign default gateway addresses.  

### **📍 Phase 2: Network Configuration in GNS3 (Demo by 29/11/2024)**  
- Build the network topology as per the diagram.  
- Configure router interfaces and test point-to-point connectivity.  
- Set up Ethernet Switches with correct VLANs.  
- Implement static and default routing.  
- Configure DHCP pools and relay agents (`ip helper-address`).  
- Enable NAT/PAT for Internet access.  

### **📍 Phase 3: Services & Applications (Demo by 16/12/2024)**  
- Deploy **Calendar** and **Horoscope** VMs.  
- Configure an **HTTP/Web Server** on each VM.  
- Develop a **Client/Server application** for the "Guess the Number" game using sockets.  

## 📂 How to Use  

1. Clone this repository and open the project files in **GNS3**.  
2. Configure routers, VLANs, and DHCP according to the provided instructions.  
3. Deploy the web servers and client-server applications.  
4. Test connectivity and ensure NAT/PAT and routing are correctly implemented.  

## 🛠️ Tools & Technologies  

- **GNS3** (for network simulation)  
- **Cisco IOS** (for router and switch configurations)  
- **Python** (for client-server application)  
- **Apache/Nginx** (for web services)  

## 🤝 Contribution  

Feel free to test, modify, and improve the project! Feedback and contributions are welcome.  

---

📌 **Author:** [Your Name]  
📌 **University:** University of Aveiro  
📌 **Course:** Communications Networks I - 2024/2025  
