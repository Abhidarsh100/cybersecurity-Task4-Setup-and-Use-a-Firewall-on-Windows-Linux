# 🔥 Task 4: Setup and Use a Firewall on Windows/Linux

## 🛠️ What I Did

This task demonstrates basic firewall configuration using Windows Defender Firewall. I blocked Telnet traffic (port 23), allowed SSH (port 22), and verified the rules.

## 📌 Steps Performed

### 1. Opened Firewall:
- Control Panel > System and Security > Windows Defender Firewall > Advanced Settings

### 2. Blocked Inbound Traffic on Port 23:
- Inbound Rule > New Rule > Port > TCP > 23 > Block connection

### 3. Tested the Rule:
- Used `telnet localhost 23` to verify block

### 4. Allowed Port 22 for SSH:
- Inbound Rule > New Rule > Port > TCP > 22 > Allow connection

### 5. Removed Block Rule:
- Inbound Rules > Right-click `Block Telnet Port 23` > Delete

## 📸 Screenshots

- `firewall-rule-port23.png` - Block rule created
- `telnet-test.png` - Failed Telnet connection
- `allow-port22.png` - Allow SSH rule
- `rule-removed.png` - Deleted port 23 block rule

## 🧠 What I Learned

- Windows Firewall allows fine-grained traffic control.
- Blocking insecure ports (like Telnet) improves system security.
- Always test and clean up rules after configuration.

