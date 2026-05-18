AutoReconX 

1. Open terminal and run:
   ```bash
   cd ~/Desktop
   nano README.md
   ```

2. Delete all old content (press `Ctrl + K` repeatedly until empty).

3. Paste the entire content below.

4. Save & Exit:  
   `Ctrl + O` → Press nter → `Ctrl + X`

---

```markdown
# AutoReconX - Kali Edition

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![Kali Linux](https://img.shields.io/badge/Platform-Kali%20Linux-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A lightweight, fast, and user-friendly reconnaissance tool developed for "educational and learning purposes" on Kali Linux.

---

## Important Disclaimer

This tool is intended for educational purposes only.

- Use this tool "only on domains you own" or have "explicit written permission" to test.
- Unauthorized scanning or reconnaissance against systems you do not own may violate laws and terms of service.
- The author is "not responsible" for any misuse or damage caused by this tool.
- Any illegal activity performed using this tool is the "sole responsibility of the user".

> "With great power comes great responsibility."

---

##  Description

"AutoReconX" is a simple yet effective Python-based reconnaissance tool that performs basic information gathering on a target domain. It is designed to help students, beginners, and security enthusiasts learn the fundamentals of reconnaissance in ethical hacking and bug bounty hunting.

---

##  Features

- DNS resolution
- HTTP & HTTPS connectivity check
- Whois information gathering
- Automatic detailed report generation
- Clean, colored terminal output using Rich & Colorama
- Organized report saving system

---

## 🛠 Requirements

- Kali Linux (Recommended)
- Python 3.10+
- Internet Connection

---

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AutoReconX.git
   cd AutoReconX
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv autoreconx-env
   source autoreconx-env/bin/activate
   ```

3. Install required packages:
   ```bash
   pip install requests colorama rich
   ```

---

## Usage

### Basic Command:
```bash
python3 autoreconx.py -t example.com
```

### Example:
```bash
python3 autoreconx.py -t testphp.vulnweb.com
```

Note: Replace `example.com` with your authorized target.

---

##  Project Structure

```
AutoReconX/
├── autoreconx.py          # Main script
├── README.md
├── autoreconx-env/        # Virtual environment (not uploaded)
└── reports/
    └── target_domain_YYYY-MM-DD_HH-MM.txt
```

---

##  Sample Output

```
========================================
       AutoReconX - Kali Edition
========================================

Target : example.com
Started: 2026-05-17 13:05:22

✓ IP Address     : 93.184.216.34
✓ HTTP Status   : 200 → http://example.com
✓ HTTPS Status  : 200 → https://example.com

[+] Running Whois...

[+] Report saved: reports/example.com_2026-05-17_13-05.txt
```

---

## Future Improvements

- Subdomain enumeration
- Port scanning with Nmap
- Screenshot capture
- Directory brute-forcing
- JSON + HTML report support
- Interactive mode

---

##  License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

##  Author

"Abu Zaber"

- Kali Linux & Cybersecurity Enthusiast
- Learning Ethical Hacking & Bug Bounty Hunting

---

 If you find this tool helpful for learning, please give it a star on GitHub!

---

Made for learning purposes with 

```

---

### Final Step:

After saving the file, check it with:
```bash
cat README.md
```

