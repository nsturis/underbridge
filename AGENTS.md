# AGENTS.md

## Project overview
Underbridge is a Python/Tkinter GUI for exporting OP-Z multitrack audio. The
main entry point is `underbridge.py`.

## Key files
- `underbridge.py`: Main application code and GUI logic.
- `README.md`: End-user setup and usage instructions.
- `dist/`: Packaged binaries (do not edit when changing source).

## Setup
- Python 3.9 is recommended.
- Install dependencies:
  - `pip install mido python-rtmidi pyaudio`
  - macOS: `brew install portaudio python-tk`
  - Ubuntu: `sudo apt install portaudio19-dev python3-tk`
- Connect the OP-Z via USB and set it as the system audio input device.

## Run
From the repository root:
```
python3 underbridge.py
```

## Tests
No automated tests are configured in this repository.
