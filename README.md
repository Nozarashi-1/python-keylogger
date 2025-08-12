## :fire: Python Keylogger

This is a Python-based keylogger that records keystrokes and periodically sends logs to a specified email address.

It is intended only for cybersecurity education, malware analysis practice, and penetration testing in controlled environments with explicit permission.

## ⚠ Disclaimer
    Do NOT run this on systems you do not own or have permission to test.
    Unauthorized use is illegal and punishable under computer crime laws.

## 📌 Features

    Captures all keystrokes using pynput

    Sends logged keys to a specified email address

    Configurable reporting interval

    Runs in the background using threads

## 🛠 Installation
Clone the repository:
``` bash
    git clone https://github.com/Nozarashi-1/python-keylogger.git
    cd python-keylogger
```

## 🚀 Usage 

1. Edit zlogger.py and replace:

        my_keylogger = keylogger.Keylogger(120, "YOUR_EMAIL", "APP PASSWORD")

2. Run the logger:

        Press some keys in any window — the logs will be printed to the terminal and sent to your test email.

## ⚖ Legal Notice

    You are responsible for ensuring all usage is authorized.

    The author assumes no liability for any misuse.    
    
