# Simple Keylogger (Educational Use Only)

Minimal example that logs keystrokes to `keyfile.txt` using `pynput`. Intended for learning and defensive security research, not covert use.

## Requirements
- Python 3.8+
- `pynput` (install with `pip install pynput`)

## How It Works
- `keyboard.Listener` hooks global keypress events.
- Character keys are appended to `keyfile.txt` in the script directory.
- Runs until you close the console or send EOF to `input()`.

## Run
```bash
pip install pynput
python keylogger.py
```

## Ethical & Legal Disclaimer
- Use only on systems you own or have explicit, informed permission to test.
- Unauthorized keylogging is illegal and unethical; laws vary by jurisdiction.
- Provided solely for education and to understand how keyloggers operate so you can defend against them.

## Limitations
- Non-character keys (Ctrl, Alt, etc.) are not stored; errors print to stdout.
- Log path is hard-coded to current working directory.
- No persistence, obfuscation, or stealth features included.
