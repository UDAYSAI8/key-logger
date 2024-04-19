
# Python Keylogger with SMTP

This Python script serves as a keylogger that captures keystrokes from a user's keyboard and sends them via email using the Simple Mail Transfer Protocol (SMTP). It can be used for various purposes such as monitoring user activity or remote administration, but it's essential to ensure that you have the appropriate permissions and legal authorization before using it.

## Features

- **Keystroke Logging**: Captures keystrokes entered by the user.
- **Email Reporting**: Sends the captured keystrokes to a specified email address.
- **Stealth Mode**: Runs in the background without displaying any visible indication to the user.

## Prerequisites

- Python 3.x installed on your system.
- Necessary Python libraries: `pynput`, `smtplib`, `email`.
- Access to a valid SMTP server to send emails.

## Usage

1. Clone this repository or download the `keylogger.py` file.
2. Install the required Python libraries by running: pip install pynput smtplib email.
3. Configure the script by modifying the following variables in the `keylogger.py` file:
- `EMAIL_ADDRESS`: Your email address.
- `EMAIL_PASSWORD`: Your email password.
4. Run the script using Python: python3 file.py
5. The keylogger will start capturing keystrokes silently in the background.
6. To stop the keylogger, terminate the Python process running the script.

## Disclaimer

This keylogger script is provided for educational purposes only. Misuse of this script for malicious purposes is strictly prohibited. Ensure that you have the legal right to monitor the activities of the users on the system where this script is deployed. The author is not responsible for any misuse or damage caused by the use of this script.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or create a pull request.

## Contact

If you have any questions or concerns, please feel free to contact the author:
- Author: Buggareddygari Udaysai Reddy
- Email: budaysaireddy@gmail.com

