🖥️ Keylogger GUI (Python)

A simple Python-based keylogger with a graphical user interface built using Tkinter and pynput.
This program captures keyboard events (pressed, held, and released) in real time and saves them to both text and JSON log files.

✨ Features

Start/Stop Controls: Easy-to-use GUI to control keylogging.

Real-Time Keystroke Tracking: Logs pressed, held, and released keys.

Dual Log Formats:

key_log.txt — Sequential raw keystrokes

key_log.json — Structured event data

Background Keyboard Listener: Uses pynput to capture key events.

Session Timestamp: Log files are associated with the current session.

📁 Output

Logs are stored in the ./out/ directory:

key_log.txt – Continuous text of captured keystrokes

key_log.json – JSON list of keystroke events such as:

{ "Pressed": "'a'" }
{ "Held": "'a'" }
{ "Released": "'a'" }

🚀 How It Works

The program sets up a keyboard listener that:

Detects when keys are pressed, held, and released

Updates log files in real time

Displays status inside a Tkinter window

Allows the user to start or stop the keylogger at any time

▶️ Running the Program

Make sure you have the required dependencies:

pip install pynput


Then run:

python keylogger.py

⚠️ Disclaimer

This project is intended strictly for educational and personal use only.
Do NOT run this program on any computer without full permission.
Unauthorized keylogging may be illegal and unethical.