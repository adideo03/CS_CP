# Packet Location Analysis Using dpkt and pygeoip

This repository is part of a mini project completed during my university studies. It serves as a network analysis tool that extracts source and destination IP addresses from Wireshark packet captures and visualizes their geographical locations using KML (Keyhole Markup Language).
## Features

- Parses `.pcap` files to extract IP packet information.
- Uses `dpkt` for packet parsing and `pygeoip` for IP geolocation.
- Generates a KML file for visualizing packet flows on geographical maps.

## Requirements

- Python 3.x
- `dpkt`
- `pygeoip`
- A GeoLiteCity database file (e.g., `GeoLiteCity.dat`)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/wireshark-packet-location-analysis.git
   cd wireshark-packet-location-analysis
   ```

2. Install the required packages:
   ```bash
   pip install dpkt pygeoip
   ```

3. Download the GeoLiteCity database and place it in the project directory.

## Usage

1. Place your `.pcap` file (e.g., `wire.pcap`) in the project directory.
2. Run the script:
   ```bash
   python main.py
   ```
3. The output will be a KML document printed to the console. You can save this output to a `.kml` file for visualization in tools like Google Earth.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or new features.
