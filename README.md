# Lumix LX10 / LX15 Web Remote Control

A lightweight, zero-dependency, single-file HTML/JS web application to remotely control Panasonic Lumix LX10 and LX15 cameras over Wi-Fi via standard CGI endpoints.

---

## Features

- **One-Click Controls:** Pre-configured buttons for essential camera operations:
  - **Handshake:** Initiate communication with the camera.
  - **REC Mode:** Switch camera mode to images recording.
  - **Capabilities:** Inspect supported camera options and capabilities (for devs only).
  - **Zoom Control:** Fast Tele / Fast Wide zoom controls.
- **Dedicated Shutter Button:** Prominent trigger button to capture photos instantly.
- **Custom CGI Command Input:** Send raw `cam.cgi` parameter strings directly to the camera (for devs only).
- **Interactive Console Log:** Real-time log console displaying outgoing requests, HTTP responses, fallback attempts, and network errors.
- **CORS Fallback:** Automatic handling of cross-origin requests with a fallback mechanism for opaque mode requests.
- **Responsive Dark Theme:** Modern, mobile-friendly dark UI optimized for smart devices and desktop screens.

---

## Prerequisites & Camera Setup

1. **Enable Wi-Fi on Camera:**
   - Turn on your Panasonic Lumix LX10 / LX15.
   - Activate Wi-Fi and choose **New Connection** -> **Remote Shooting & View**.
2. **Connect your Device:**
   - Connect your laptop, phone, or tablet to the camera's Wi-Fi network.

---

## Quick Start

Since this application consists of a single standalone HTML file, no build tools or servers are required.

Clone or download the `index.html` file into your computer or smartphone. If you have a free hosting, you can upload the file.

Or try the live web interface: [Lumix LX10/LX15 Remote Control](https://goodstone.altervista.org/lx15/)
