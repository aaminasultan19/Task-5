# Task 5 Report – Protocol Analysis using Wireshark

---

##  Screenshot

Below is a screenshot of the Wireshark session used to capture and analyze the traffic:

![Wireshark Capture Screenshot](./wireshark_capture_screenshot.png)

---

##  Protocols Identified

### 1. TCP (Transmission Control Protocol)
- Used for reliable communication between devices.
- Example: Data transfer between local machine and `148.113.9.137`.

### 2. DNS (Domain Name System)
- Resolves domain names to IP addresses.
- Example: Query for `sadownload.mcafee.com` and its CNAME.

### 3. HTTP (Hypertext Transfer Protocol)
- Used to transfer web content.
- Example: HTTP GET request to download `/dd.xml` from McAfee.

### 4. ARP (Address Resolution Protocol)
- Maps IP addresses to MAC addresses on the local network.
- Example: ARP request for `192.168.1.12`.

### 5. mDNS (Multicast DNS)
- Resolves local network service names (e.g., `_spotify-connect._tcp.local`).

---


##  Conclusion
The Wireshark capture session demonstrates successful identification of various protocols in both local and external communications, improving hands-on network analysis skills.
