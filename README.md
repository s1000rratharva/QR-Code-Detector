# QR Code Risk Scanner

## Problem Statement

As QR codes become increasingly common in daily life—from restaurant menus to event tickets—they have also become a potential vector for malicious links. Malicious QR codes can redirect users to phishing websites, malware, or other harmful destinations without their knowledge. To address this concern, this project provides a simple web-based QR code scanner that can detect and decode QR codes and verify the safety of the embedded URL using the Google Safe Browsing API.

---

## Features

- *QR Code Upload*: Users can upload an image containing a QR code.
- *QR Code Decoding*: The system uses the jsQR JavaScript library to decode QR codes in-browser.
- *URL Safety Check*: The decoded URL is checked against the Google Safe Browsing API to determine if it's safe or malicious.
- *Instant Feedback*: The app displays the URL with a clear visual indication of its safety status.

---

## Technologies Used

- HTML5 & CSS3
- JavaScript (Vanilla)
- [jsQR](https://github.com/cozmo/jsQR) — For QR code decoding
- Google Safe Browsing API — For URL safety checks

---

## Setup Instructions

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox)
- An internet connection
- A Google Safe Browsing API key (free from Google's developer console)

### Running the App

1. Download or clone this repository.


2. Open the index.html file in your browser.


3. Upload a QR code image and the app will:

Decode the QR code

Show the embedded URL

Check the URL’s safety and display the result



> Note: Make sure your browser allows JavaScript and that you’ve added your Google API key to the script where applicable.

---

License

This project is licensed under the MIT License — see the LICENSE file for details.


---

Disclaimer

This application is intended for educational and demonstrative purposes only. Although it integrates with the Google Safe Browsing API for threat detection, no tool can provide absolute protection. Use responsibly. The author is not responsible for any damages or misuse resulting from the use of this tool.

Let me know if you also want the sample code structure or a ZIP version of the project folder to go with this.
