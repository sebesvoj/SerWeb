# SerWeb

**Author:** Sebesvoj for FreshPoint

SerWeb is a simple, offline-capable Serial Monitor for Arduino and other serial devices, running directly in your browser. No installation required—just open the HTML file!

## Features
- Works offline (open the HTML file directly from your computer)
- Connects to serial devices (e.g., Arduino) via Web Serial API
- Real-time display of incoming serial data
- Send text commands to your device

## Usage
1. Download or clone this repository.
2. Open `serweb.html` in Chrome, Edge, or Opera.
3. Click "Connect" and select your serial device.
4. View incoming data and send commands.

## Requirements
- Chromium-based browser (Chrome, Edge, Opera) with Web Serial API support

## Limitations
- Does not work in Firefox or Safari (Web Serial API is not supported)
- Some browsers may require HTTPS, but `file://` access generally works for local files

## License
MIT

&copy; 2025 Sebesvoj for FreshPoint
