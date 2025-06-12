## 🛰️ Nmap Tool - Network Scanning

Nmap is a powerful tool used to scan and discover devices on a network.

### 🔍 What is Nmap used for?

1. Scan all devices connected to the same network.
2. Detect open ports on a specific IP or host.
3. Discover the services running on each port.
4. Identify the operating system (OS) of the target device.
5. Perform vulnerability scanning (with scripts).

---

### 🛠️ Example Nmap Commands:

- `nmap 192.168.1.1` → Scan a specific IP.
- `nmap 192.168.1.0/24` → Scan the full local network.
- `nmap -sV 192.168.1.1` → Detect services and versions.
- `nmap -O 192.168.1.1` → Detect the operating system.
- `nmap -A 192.168.1.1` → Aggressive scan (OS + services + scripts).

---

### 🧠 Notes:
- Make sure you have permission before scanning any network.
- Use `sudo` for some advanced scans on Linux.
