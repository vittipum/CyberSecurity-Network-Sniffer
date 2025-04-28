# CyberSecurity Network Sniffer 🛡️

![GitHub release](https://img.shields.io/github/release/vittipum/CyberSecurity-Network-Sniffer.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to the **CyberSecurity Network Sniffer** repository! This lightweight Python-based network scanner detects and lists all devices on your local network using IP and MAC addresses. Built with the powerful Scapy library, this tool is perfect for cybersecurity and network analysis tasks.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Lightweight**: Minimal dependencies make it easy to set up and run.
- **Device Detection**: Quickly identifies all devices on your local network.
- **IP & MAC Address Listing**: Displays both IP and MAC addresses for easy identification.
- **Open Source**: Contribute and improve the tool with your ideas.
- **Scapy Integration**: Leverage the capabilities of Scapy for powerful network analysis.

## Installation

To get started with the CyberSecurity Network Sniffer, follow these simple steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/vittipum/CyberSecurity-Network-Sniffer.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd CyberSecurity-Network-Sniffer
   ```

3. **Install the required dependencies**:

   Make sure you have Python and pip installed. Then run:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the latest release**:

   You can find the latest release [here](https://github.com/vittipum/CyberSecurity-Network-Sniffer/releases). Download the file, and follow the instructions to execute it.

## Usage

Using the CyberSecurity Network Sniffer is straightforward. Once installed, you can run the scanner with a simple command.

### Basic Command

To start scanning your local network, use:

```bash
python sniffer.py
```

This command will begin the scan and display a list of devices connected to your network.

### Command Line Options

You can customize your scan using various command line options:

- `-h`, `--help`: Show help message and exit.
- `-i`, `--interface`: Specify the network interface to use (e.g., `eth0`, `wlan0`).
- `-r`, `--range`: Define the IP range to scan (e.g., `192.168.1.1/24`).

### Example Command

To scan a specific interface and range, you can run:

```bash
python sniffer.py -i wlan0 -r 192.168.1.0/24
```

This command scans the specified range on the given interface.

## Examples

Here are some examples of how to use the CyberSecurity Network Sniffer effectively:

### Scanning the Entire Network

To scan the entire local network, simply run:

```bash
python sniffer.py
```

You will see output similar to:

```
Scanning...
Device 1: IP - 192.168.1.10, MAC - 00:14:22:01:23:45
Device 2: IP - 192.168.1.11, MAC - 00:14:22:01:23:46
...
```

### Specifying an Interface

If you want to scan a specific network interface, use the `-i` option:

```bash
python sniffer.py -i eth0
```

### Scanning a Specific IP Range

To limit your scan to a specific range, use the `-r` option:

```bash
python sniffer.py -r 192.168.1.0/24
```

## Contributing

We welcome contributions to improve the CyberSecurity Network Sniffer. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request explaining your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Author**: Vittipum
- **Email**: vittipum@example.com
- **GitHub**: [vittipum](https://github.com/vittipum)

## Releases

For the latest updates and releases, visit the [Releases](https://github.com/vittipum/CyberSecurity-Network-Sniffer/releases) section. Download the latest version and start using it today.

---

Thank you for checking out the CyberSecurity Network Sniffer! We hope you find it useful for your network analysis and cybersecurity tasks.