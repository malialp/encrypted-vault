# File Encryption App

## Overview

This is a Python-based file encryption and decryption application. The app allows users to encrypt and decrypt files using a symmetric encryption algorithm (AES). It is designed to protect sensitive information by converting plain text files into unreadable formats and restoring them to their original form when required.

## Features

- Encrypt files using AES (Advanced Encryption Standard)
- Decrypt files back to their original state
- Password-based encryption (PBKDF2) for secure key generation
- Support for all file formats.

## Installation

You can install the required Python libraries using the following command:

```bash
pip install -r requirements.txt
```

Run vault.py.

```bash
python vault.py
```

When you first run the app will create a folder named "vault" and a salt file named "salt.salt". Put the files you want to encrypt inside the vault folder.

## Warning

Do not delete salt.salt file after encryption. Else you can't decrypt your files even you know your password. You need to have both your password and salt file to decrypt your files.
