# Network Traffic Monitor

This project contains a tool for real-time network traffic monitoring and analysis using Scapy and Pandas.

## Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/network-traffic-monitor.git
cd network-traffic-monitor
pip install -r requirements.txt
```
# Usage

Run the monitor tool:

```bash

sudo python src/monitor.py -i <network_interface> -o <output_csv_file>
```
Replace <network_interface> with the name of the network interface you want to monitor (e.g., eth0, wlan0), and <output_csv_file> with the name of the output CSV file.
