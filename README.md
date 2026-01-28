# Simple Keylogger (educational use only)

> Minimal example that logs keystrokes to `keyfile.txt` using `pynput`.

## Requirements
- Python 3.8+ on Windows, macOS, or Linux
- `pynput` library: `pip install pynput`

## How it works
- `keyboard.Listener` hooks global keypress events.
- Every key press is appended to `keyfile.txt` (created in the script directory).
- Script runs until you close the console (or send EOF to `input()`).

## Run
```bash
pip install pynput
python keylogger.py
