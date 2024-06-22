### Harmoni Cloner

This Python script allows you to clone roles, channels, and categories from one Discord server to another.

#### Prerequisites

Before running the script, ensure you have the following dependencies installed:
- Python 3.x
- Required Python packages (`requirements.txt`)

#### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

#### Usage

1. Modify `start.bat` to suit your environment.
   - Ensure `python` in the script points to your Python executable.

2. Configure `Cloner.py`:
   - Replace `<your_token>` with your Discord user token.
   - Update `<guild_s>` and `<guild>` with the source and destination server IDs.

3. Run `start.bat` to initiate the cloning process.

#### Files

- `start.bat`: Script to automate dependencies installation and script execution.
- `Cloner.py`: Main script to clone roles, channels, and categories between Discord servers.
- `serverclone.py`: Contains the `Clone` class with methods for Discord server cloning.
- `requirements.txt`: List of Python packages required by the script.

#### Notes

- This script is intended for educational purposes and should be used responsibly.
- Ensure you have necessary permissions and consent before using this script on Discord servers.

#### Disclaimer

Use this script at your own risk. The author takes no responsibility for any misuse or damage caused.
