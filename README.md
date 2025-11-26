# Shai-Hulud-Detector
Shai-Hulud Detector and Scanner

A lightweight Python tool to detect Shai-Hulud v2 malware and supply chain threats in software projects.  
It scans key files and directories for suspicious scripts, secrets, and malicious patterns — with risk classification and secure execution.

🚀 Features

 🔍 Scans package.json, pom.xml, Dockerfiles, GitHub Actions, .env, and more  
 🧠 Detects suspicious scripts, secrets, and malware indicators  
 🛡️ Secure by design: no shell injection, safe subprocesses, auto cleanup  
 📊 Classifies risks as CRITICAL, HIGH, MEDIUM, or LOW  
 📝 Generates detailed logs and reports


⚙️ Installation & Usage
# Clone the repo
git clone https://github.com/Dark-Ghost-x/Shai-Hulud-Detector.git
cd Shai-Hulud-Detector

# Scan a Git repository
python3 Shai-Hulud-Detector-and-Scanner --repo https://github.com/Dark-Ghost-x/sms-ch

# Scan a zip archive
python3 Shai-Hulud-Detector-and-Scanner --file project.zip

# Scan a local directory
python3 Shai-Hulud-Detector-and-Scanner --path /home/user/project



## ⚠️ Disclaimer

## This is an early-stage tool and may contain bugs or false positives.  
## If you encounter any issues, feel free to report them directly to the developer via Telegram.
