# Phishing URL Detector

## Description
This is a simple Python script designed to detect potential phishing URLs. It checks for common phishing keywords, suspicious patterns such as IP addresses in URLs, and multiple subdomains that might indicate phishing attempts.

## Features
- Detects phishing keywords in URLs (e.g., "login", "verify", "password").
- Identifies suspicious patterns like IP addresses in URLs.
- Flags URLs with multiple subdomains.
- Provides warnings for potentially harmful URLs.

## Requirements
- Python 3.x

## Installation
1. Clone this repository or download the script.
   ```sh
   git clone https://github.com/Eshwarsai-07/phishing-url-detector.git
   cd phishing-url-detector
   ```
2. Ensure you have Python installed. You can check by running:
   ```sh
   python --version
   ```

## Usage
1. Run the script:
   ```sh
   python phishing_detector.py
   ```
2. The script will check URLs against predefined phishing indicators.
3. Example list of URLs can be modified in the script.

## Example
```
Potential phishing URL detected: http://login-bank.com
Suspicious URL detected: http://192.168.1.1
Suspicious URL detected: http://secure-login.example.com
Potential phishing URL detected: http://update-password.com
URL seems safe: http://example.com
URL seems safe: http://go0gle.com
```

## License
This project is licensed under the MIT License.

## Contributions
Feel free to fork this repository, submit issues, or create pull requests to improve the script!

## Author
[Eshwar Sai](https://github.com/Eshwarsai-07)