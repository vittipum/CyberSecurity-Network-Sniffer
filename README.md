# 🔍 CyberSecurity Network Sniffer

A simple but effective Python-based network scanner that detects devices connected to your local network, displaying their IP and MAC addresses.

This project contains two basic scanners built using **Scapy**, designed for quick device enumeration within a specified subnet.

---

## 📁 Project Files

### `Sniff_Tool.py`
- Uses `argparse` and `scapy`.
- Syntax:  
  ```bash
  sudo python Sniff_Tool.py -ip <ip_address>/<subnet>

- Example:  
  ```bash
  sudo python Sniff_Tool.py -ip 192.168.1.1/24
  ```

### `Sniff_Tool2.py`
- Uses `sys` and `scapy`.
- Syntax:  
  ```bash
  sudo python Sniff_Tool2.py <ip_address>/<subnet>
  ```
- Example:  
  ```bash
  sudo python Sniff_Tool2.py 192.168.1.1/24
  ```

---

## ⚙️ Requirements

- Python 3.x
- `scapy`  
  Install using:
  ```bash
  pip install scapy
  ```
- `argparse` (comes built-in with Python)

> 💡 **Run the scripts with root or administrative privileges.**  
> These tools rely on packet sniffing which requires elevated permissions.

---

## 🧪 Sample Output

```json
{'ip': '192.168.1.1',  'mac': '7c:a9:6b:07:6e:14'}
{'ip': '192.168.1.3',  'mac': '88:11:96:ff:79:a0'}
{'ip': '192.168.1.10', 'mac': '68:db:f5:84:80:7f'}
{'ip': '192.168.1.4',  'mac': 'd4:f5:47:17:b0:a6'}
{'ip': '192.168.1.14', 'mac': 'a4:c3:f0:4f:a5:06'}
{'ip': '192.168.1.2',  'mac': '6c:56:97:b0:fe:b3'}
{'ip': '192.168.1.26', 'mac': '28:6c:07:8c:96:f5'}
```

---

## 🔐 Disclaimer

This tool is intended **for educational and ethical use only**. Always get proper authorization before scanning networks.

