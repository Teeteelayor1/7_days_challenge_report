# **7-Days Cybersecurity Challenge**

# **Day 2**
## **Network Traffic Monitoring And Packet Analysis**
**Install Wireshark:**
- Run: `sudo apt install wireshark -y` (Linux) or download from [Wireshark's website](https://www.wireshark.org/). (Don't bother installing wireshark if you're using kali)
2. **Capture Network Traffic:**
   - Open Wireshark, select an active network interface, and start capturing.
   - Filter packets using:
     - `http` (for web traffic)
     - `dns` (for domain name lookups)
     - `icmp` (for ping requests)
   
3. **Analyze a PCAP File:**
   **PCAP file** (Download from [https://wiki.wireshark.org/uploads/27707187aeb30df68e70c8fb9d614981/http.cap)).
   - Look for credentials sent in plaintext (**HTTP, FTP, Telnet** traffic).
   
4. **Identify Suspicious Activity:**
   - Look for large data transfers.
   - Check for multiple failed login attempts.
   - Find unexpected IP addresses communicating with your machine.
