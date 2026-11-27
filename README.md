# Identification of Standard Network Hardware Components and Troubleshooting Connectivity Issues in a Small Office Network

## 📌 Project Overview

This project focuses on identifying standard network hardware components and troubleshooting common connectivity problems in a small office network.

It explains the functions of network devices, demonstrates star topology, configures IP addressing, and uses Windows network diagnostic commands to identify and resolve connectivity issues.

## 🎯 Objectives

- Identify network hardware components such as NICs, switches, routers, modems, and Ethernet cables.
- Understand star topology and small office network architecture.
- Configure IP addresses, subnet masks, default gateways, and DNS servers.
- Learn Windows network diagnostic commands.
- Troubleshoot common network connectivity problems.
- Understand practical network implementation and testing.

## 🛠️ Hardware Components Used

| Component | Quantity | Purpose |
|---|---:|---|
| Computers | 5 | Connect to the office network |
| Gigabit Switch | 1 | Connect computers within the LAN |
| Router | 1 | Connect the LAN to the internet |
| Cat6 Ethernet Cables | 6 | Connect network devices |
| ISP Modem / Fibre Terminal | 1 | Provide internet connectivity |

## 🌐 Network Topology

The project uses **Star Topology**, in which five computers connect to a central switch. The switch connects to a router, which provides internet connectivity through the ISP modem.

### Network Configuration

- Network Address: `192.168.1.0/24`
- Router IP: `192.168.1.1`
- Subnet Mask: `255.255.255.0`
- Preferred DNS: `8.8.8.8`
- Alternate DNS: `8.8.4.4`

### IP Address Allocation

| Device | IP Address |
|---|---|
| Router | 192.168.1.1 |
| PC1 | 192.168.1.11 |
| PC2 | 192.168.1.12 |
| PC3 | 192.168.1.13 |
| PC4 | 192.168.1.14 |
| PC5 | 192.168.1.15 |

## 💻 Network Diagnostic Commands

The following Windows commands are used to check network connectivity:

| Command | Purpose |
|---|---|
| `ipconfig` | Displays IP configuration |
| `ipconfig /all` | Displays detailed network information |
| `ping` | Tests network connectivity |
| `tracert` | Tracks the route to a destination |
| `nslookup` | Checks DNS resolution |
| `netstat -an` | Displays network connections and ports |
| `arp -a` | Displays IP-to-MAC address mappings |

## 🔧 Network Troubleshooting

Four common network problems are introduced and resolved in this project.

| Fault | Problem | Solution |
|---|---|---|
| F1 | Unplugged Ethernet cable | Reconnect the cable |
| F2 | Duplicate IP address | Assign a unique IP address |
| F3 | Incorrect default gateway | Set the correct gateway |
| F4 | Incorrect DNS server | Configure a working DNS server |

## ⚙️ Practical Implementation

1. Connect the router to the ISP modem.
2. Connect the router to the central switch.
3. Connect all five computers to the switch using Cat6 cables.
4. Configure static IP addresses on each computer.
5. Verify network settings using `ipconfig /all`.
6. Test connectivity using `ping` and other diagnostic commands.
7. Introduce network faults one at a time.
8. Identify and resolve each problem.
9. Test the network again after applying the fixes.

## 📊 Results

The project demonstrates successful network communication between computers and the router.

The four introduced faults were identified and resolved:

- The unplugged cable was reconnected.
- The duplicate IP address was replaced with an unused address.
- The incorrect default gateway was corrected.
- The incorrect DNS server was replaced with a working DNS server.

The results demonstrate how systematic troubleshooting helps identify network problems efficiently.

**Note:** The report contains sample command outputs. Actual laboratory screenshots and test results can be added when available.

## 📚 Applications

The concepts covered in this project are useful in:

- Small offices and business networks.
- Schools and college computer laboratories.
- Hospitals and clinics.
- Banks and retail stores.
- IT companies and call centres.
- Home and local area networks.

## 📖 References

1. Computer Networks – A. S. Tanenbaum and D. J. Wetherall.
2. Data Communications and Networking – B. A. Forouzan.
3. Computer Networking: A Top-Down Approach – Kurose and Ross.
4. Microsoft Learn – Windows Networking Commands.
5. IEEE 802.3 Ethernet Standard.
6. IETF Networking Standards and RFC Documents.

## 👨‍🎓 Student Details

- **Name:** Veeraboina Naga Chaitanya Kumar
- **Roll Number:** 25MVCSER0449
- **Course:** B.Tech – Computer Science Engineering
- **Year/Semester:** 2nd Year / 4th Semester
- **Subject:** Computer Networks (Practical)
- **Institution:** Malla Reddy Vishwavidya Peeth
- **Academic Year:** 2026–2027

## ✅ Conclusion

This project provides practical knowledge of network hardware, IP configuration, star topology, network diagnostic commands, and troubleshooting techniques. It demonstrates how common connectivity problems in a small office network can be identified and resolved through a systematic approach.
