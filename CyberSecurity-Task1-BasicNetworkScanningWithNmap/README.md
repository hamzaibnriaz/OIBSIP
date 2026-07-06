# Cyber Security Task 1 - Basic Network Scanning with Nmap

## Objective
Perform basic network scanning using Nmap to discover active hosts, open ports, services, and operating system information.

## Tools Used
- Kali Linux
- Nmap
- VMware

## Commands Used

### Check Nmap Version
```bash
nmap --version
```

### Find Local IP Address
```bash
hostname -I
```

### Basic Scan
```bash
nmap 192.168.100.167
```

### Service Version Detection
```bash
nmap -sV 192.168.100.167
```

### Operating System Detection
```bash
sudo nmap -O 192.168.100.167
```

## Results

- Nmap was successfully installed.
- Local IP address was identified.
- Host was reachable.
- No open ports were detected.
- Service version detection did not find any running services.
- OS detection could not accurately identify the operating system because all ports were filtered.

## Screenshots

![Nmap Version](screenshots/01_nmap_version.png)

![Hostname IP](screenshots/02_hostname_ip.png)

![Basic Scan](screenshots/03_basic_nmap_scan.png)

![Service Version Scan](screenshots/04_service_version_scan.png)

![OS Detection](screenshots/05_os_detection_scan.png)

## Conclusion

This task demonstrated how to use Nmap for basic network scanning, service detection, and operating system detection. The target host was reachable, but all scanned ports were filtered, so no active services or operating system details could be identified.
