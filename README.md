# File Decryption Script

This Python script decrypts files that have been encrypted using the `cryptography.fernet` library. It allows the user to provide a valid decryption key and a filename to decrypt the file.

## Features

- Decrypt encrypted files using the provided decryption key.
- Display status messages to indicate the success or failure of the decryption process.

## Prerequisites

Before running the script, ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/) (recommended version: 3.7+)
- `cryptography` library (can be installed using `pip`)

## Installation

1. Clone the repository or download the script file.

2. Install the required library:

   ```bash
   pip install cryptography
Usage
Run the script:

```bash
python3 deKey.py
```
## The script will prompt you to input the following:
-Enter the valid Key: The decryption key that was used to encrypt the file. Make sure the key is valid and correctly formatted.
-Choose the file name: The name of the encrypted file you want to decrypt. The file must be in the same directory as the script.

Example output:

```pgsql

Enter the valid Key: <your_decryption_key>
Choose the file name (must be in the same path): <encrypted_filename>.encrypted
```
The script will attempt to decrypt the file. If successful, the decrypted file will be saved with the same name as the original file but without the .encrypted extension. If there’s an error, such as an invalid key or missing file, an error message will be displayed.

## Example
-If you have a file named document.txt.encrypted, you would:
  -Enter the decryption key.
  -Provide the filename document.txt.encrypted.

-The script will create the decrypted file document.txt in the same directory.

This project is licensed under the MIT License.







