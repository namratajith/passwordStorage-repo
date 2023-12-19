Secure Password Manager
This Python script serves as a secure password manager utilizing the cryptography library's Fernet encryption to store and retrieve passwords.

Features
Encryption: Uses Fernet encryption to securely store passwords in a file.
Adding Passwords: Allows users to add new account credentials by specifying the account name and password.
Viewing Passwords: Provides the functionality to view existing stored account credentials.
How to Use
Setup:

Ensure you have Python installed.
Run write_key() once to generate the encryption key (already provided in the script). This generates a key.key file containing the encryption key.
Run the Script:

Launch the script in your Python environment.
Enter the master password when prompted.
Usage:

Choose add to input new account credentials.
Choose view to see the stored account names and their encrypted passwords.
Exiting:

Press q to quit the script.
Security Note
Master Password: The script requires a master password that should be kept secure as it's used to access the encrypted passwords.
Encryption Key: Ensure the key.key file containing the encryption key is stored securely and not shared with anyone.
