# Task 2 - Configure and Use a Firewall

## Objective
Configure and manage a firewall using UFW (Uncomplicated Firewall) on Kali Linux.

## Tools Used
- Kali Linux
- UFW (Uncomplicated Firewall)

## Commands Used

### Update Packages
```bash
sudo apt update
```

### Check UFW Version
```bash
ufw --version
```

### Check Firewall Status
```bash
sudo ufw status
```

### Enable Firewall
```bash
sudo ufw enable
```

### Allow SSH (Port 22)
```bash
sudo ufw allow 22
```

### Block HTTP (Port 80)
```bash
sudo ufw deny 80
```

### Allow HTTPS (Port 443)
```bash
sudo ufw allow 443
```

### Verify Firewall Rules
```bash
sudo ufw status numbered
```

## Result

Successfully configured the firewall.

- Allowed SSH (Port 22)
- Blocked HTTP (Port 80)
- Allowed HTTPS (Port 443)

Firewall Status: Active

## Screenshots

All screenshots are available in the screenshots folder.
