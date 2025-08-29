Caesar Cipher

A simple Python project that implements the classic Caesar Cipher for encoding and decoding secret messages.
Built as part of my Python learning journey.

About the Caesar Cipher

The Caesar Cipher is one of the oldest and simplest encryption techniques.
It works by shifting each letter in the message by a fixed number of positions in the alphabet.

Example:

Encode "abc" with shift 3 → "def"

Decode "def" with shift 3 → "abc"

Features

Encrypt messages with a custom shift

Decrypt messages back to original text

Handles spaces, numbers, and symbols (keeps them unchanged)

ASCII art logo for a fun interface

Option to restart the program without rerunning

Installation & Usage

Clone the repository:

git clone https://github.com/YOUR_USERNAME/caesar_cipher.git
cd caesar_cipher


Create and activate a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


Run the program:

python main.py

Project Structure
caesar_cipher/
│── cipher.py       # Main program
│── art.py        # ASCII art logo
│── .gitignore    # Ignore venv, cache, etc.
│── README.md     # Project documentation
│── venv/         # Virtual environment (ignored in Git)

Example Run

LOGO

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
Here is the encoded result: mjqqt btwqi
Type 'yes' if you want to go again. Otherwise type 'no'.
