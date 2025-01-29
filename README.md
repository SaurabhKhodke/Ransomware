# Ransomware Using Python

## ⚠️ Caution
**This ransomware program is malicious and has the potential to cause irreversible data loss. Use it responsibly and only in ethical and legal contexts. This program can affect all types of files, so handle it with extreme caution.**

## 🚀 Overview
You can use the following scripts:
- `Destruction.py`: Encrypts all files in a folder.
- `Construction.py`: Decrypts all files in a folder.

Additionally, precompiled executables are available:
- `Setup.exe`: Executable for `Destruction.py`.
- `Uninstall.exe`: Executable for `Construction.py`.

## 🔧 Setting Up the Program
To install the required dependency, run:
```bash
pip install cryptography
```

## 🛠️ Creating Executable Files
To generate `.exe` files from the Python scripts, install `pyinstaller`:
```bash
pip install pyinstaller
```
Then, create the executables:
```bash
pyinstaller --onefile destruction.py
pyinstaller --onefile construction.py
```
**💡 Tip:** The `--onefile` command is crucial as it allows the `.exe` files to run even on systems that do not have Python installed.

## ▶️ Running the Scripts
To encrypt files:
```bash
python destruction.py
# or run Setup.exe
```

To decrypt files:
```bash
python construction.py
# or run Uninstall.exe
```
![Running destruction.py/ Setup.exe](path/to/screenshot.png)

![Key Generated](path/to/screenshot.png)

![Encrypted Files](path/to/screenshot.png)

Running construction.py/ Uninstall.exe

![Wrong Password](path/to/screenshot.png)

![Correct Password](path/to/screenshot.png)

![Decrypted Files](path/to/screenshot.png)

## 📜 Disclaimer
This project is for **educational purposes only**. Any misuse of this tool for illegal activities is **strictly prohibited**. The author assumes no responsibility for any harm or damage caused by this software.

