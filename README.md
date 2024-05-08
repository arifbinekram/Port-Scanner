

# Port-Scanner

## Overview
Port-Scanner is a Python-based tool designed to scan a specified IP address range for open ports. This tool can be used to identify open ports on a single host or across a network segment, which is crucial for network security assessments.

## Features
- Simple and intuitive command-line interface.
- Ability to scan individual or multiple hosts.
- Customizable port ranges.
- Option for verbose output to get more detailed scan information.

## Installation
To use Port-Scanner, clone the repository to your local machine:
```
git clone https://github.com/arifbinekram/Port-Scanner.git
```
Navigate to the directory where you cloned the repo:
```
cd Port-Scanner
```

## Usage
To perform a scan, run the script with the required parameters. For example, to scan a single IP address for open ports:
```
python PortScan.py --host <ip_address>
```
For a more detailed scan with verbose output:
```
python PortScan.py --host <ip_address> -v
```
Replace `<ip_address>` with the actual IP address you wish to scan.
