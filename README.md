# Python Keylogger

A simple keylogger implemented in Python using the `pynput` library. This program captures keystrokes and logs them to a text file. It is intended for educational purposes and should be used responsibly.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Legal Considerations](#legal-considerations)
- [License](#license)

## Features

- Captures all keystrokes, including special keys.
- Logs keystrokes to a text file (`log.txt`).
- Stops logging when the `Esc` key is pressed.

## Installation

To run this keylogger, follow these steps:

1. **Clone the Repository**:
git clone https://github.com/yourusername/keylogger_project.git
cd keylogger_project
text

2. **Install Required Libraries**:
Make sure you have Python installed on your system. Then, install the `pynput` library using pip:
pip install pynput
text

## Usage

1. **Run the Keylogger**:
Open a terminal or command prompt, navigate to the project directory, and run the following command:
python keylogger.py
text

2. **Stop Logging**:
To stop the keylogger, press the `Esc` key.

3. **View Logs**:
Open `log.txt` to view the captured keystrokes.

## Folder Structure

keylogger_project/
│
├── keylogger.py # Main keylogger script
├── log.txt # File where keystrokes will be logged
└── README.md # Documentation about the project
text

## Legal Considerations

**IMPORTANT**: Using a keylogger without consent is illegal and unethical. Ensure you have explicit permission from any user whose keystrokes you intend to log. This tool is intended for educational purposes only and should not be used for malicious activities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
