# Password Manager

A simple Password Generator and Manager application built using Python and Tkinter. This tool helps you generate strong passwords and securely store them for various websites.
Used a .json file as backend database for storing saved passwords with the appropriate websites, and fetches them when required.

## Features

- **Password Generator**:
  - Generate random, secure passwords.
  - Includes a mix of letters, numbers, and symbols.
  - Automatically copies the password to your clipboard.

- **Password Manager**:
  - Save website credentials (email/username and password).
  - Search for saved passwords by website name.
  - Store data securely in a `data.json` file.

- **User-Friendly Interface**:
  - Easy-to-use graphical user interface (GUI) built with Tkinter.
  - Buttons for generating, saving, and searching passwords.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/password-manager.git
   cd password-manager
   ```
2. Install required dependencies:
This project uses the pyperclip module for clipboard operations. Install it using:

```bash
pip install pyperclip
```

3. Ensure you have a file named logo.png in the same directory as the script for the application logo.
Make sure you have a logo.png(or any logo file)file in your project directory so that the application can load it for the GUI.

4. Run the application:
```bash
python password_manager.py
```
## Usage

### Generate a Password:
Enter the website and your email/username.
Click "Generate Password" to create a secure password.
The password will be automatically copied to your clipboard.
### Save Credentials:
After generating a password, click "Add" to save the credentials (website, email, and password).
These credentials will be stored in the data.json file.
### Search for a Password:
Enter the website name and click "Search" to retrieve saved credentials.
### Data Storage:
All passwords are stored in a data.json file in JSON format.

## File Structure

```plaintext
password-manager/
├── data.json        # File to store credentials (auto-generated)
├── logo.png         # Logo for the application
├── password_manager.py # Main Python script
```

## Requirements
Python 3
pyperclip module
To install the required Python package, run the following command:
bash
```
pip install pyperclip
```
