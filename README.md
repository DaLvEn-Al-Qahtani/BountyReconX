# BountyReconX

A fast and lightweight asynchronous web reconnaissance framework designed for Bug Bounty Hunters and Penetration Testers.

BountyReconX automates the early stages of web application reconnaissance by collecting valuable information from a target, including hidden resources, JavaScript endpoints, exposed files, URL parameters, and common security misconfigurations.

---

## Overview

BountyReconX was developed to simplify repetitive reconnaissance tasks while maintaining speed, readability, and flexibility. The framework uses asynchronous requests to efficiently gather information without unnecessary overhead.

Its modular design allows individual components to be executed independently or combined into a complete reconnaissance workflow.

---

## Features

- Asynchronous HTTP Engine
- Hidden Path Discovery
- Recursive Website Crawling
- JavaScript File Analysis
- Endpoint Extraction
- URL Parameter Collection
- Sensitive File Detection
- Security Header Inspection
- Basic OWASP Top 10 Indicators
- Automatic JSON Report Export
- Automatic TXT Report Export
- Adjustable Thread Count
- Configurable Crawling Depth

---

## Installation

Clone the repository

```bash
git clone https://github.com/DaLvEn-Al-Qahtani/BountyReconX.git
```

Move into the project

```bash
cd BountyReconX
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run every available module

```bash
python BountyReconX.py -u https://example.com --all
```

Run specific modules

```bash
python BountyReconX.py -u https://example.com --paths

python BountyReconX.py -u https://example.com --crawl

python BountyReconX.py -u https://example.com --js

python BountyReconX.py -u https://example.com --top10

python BountyReconX.py -u https://example.com --sensitive
```

---

## Output

After the scan is complete, the framework can automatically generate reports in multiple formats.

```
BountyReconX_example.com.json

BountyReconX_example.com.txt
```

---

## Project Structure

```
BountyReconX
│
├── BountyReconX.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Requirements

- Python 3.10+
- aiohttp
- beautifulsoup4
- colorama

---

## Disclaimer

This project is intended exclusively for educational purposes and authorized security assessments.

Users are solely responsible for ensuring that all scans are performed against systems they own or have explicit permission to test.

The author assumes no responsibility for misuse or damage resulting from the use of this software.

---

## Author

**DaLvEn Al-Qahtani**

Offensive Security • Bug Bounty • Web Application Security

---

## License

This project is licensed under the MIT License.
