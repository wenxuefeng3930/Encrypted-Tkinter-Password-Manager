# Encrypted-Tkinter-Password-Manager
A small python-based password manger/generator utilizing Fernet Symmetric Encryption, SQLite, and Tkinter.

## How does it work?
This uses <a href='https://cryptography.io/en/latest/fernet/'>Fernet Encryption </a>, to encrypt your master password and .db file where your passwords are stored. The GUI is based on Tkinter which allows for easy integration, with sqlite3 and Fernet.

## Security
This program is completely offline and you can view the source code to see that it isn't sending anything over the web. Plus, the key is stored on your device so it will take a long time for someone to completely decrypt the file or the master password without the key. 

## Privacy
I respect your privacy thus this program is completly offline as I've told you. Each key is unique to you and a person without the key will have a very hard time trying to decrypt it.

## Releases
It supports MacOS, Windows, and Linux. I only have windows and mac machines so you have to compile it yourself or run the file as .py instead if you're on linux.

Releases are located <a href='https://github.com/Parinz/Tkinter-Password-Manager/releases/tag/1.0'> ***HERE*** </a>
