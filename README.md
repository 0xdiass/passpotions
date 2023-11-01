# PassPotions
This is a simple password manager, Personal Project

This project will be done using python:

CheckList:
- [ ] CLI interface
    - [ ] Create Password
        - [ ] Generate Password
        - [ ] User input password (configure policy)
    - [ ] Remove Password
    - [ ] Change Password
    - [ ] List all Passwords


Notes:

For now passwords will be stored in cleartext on the current location in a file called `passwords.json`

Project Structure:

For now is going to be like this:

`main.py` -- Main Application entry point

`passpotions` -- Contatins logic about password manager.

`storage` -- Is resposible for data storage.

`encryption` -- handles encryption and decryption.

`user_interface` -- holds the user interface code, such as CLI and later GUI for example

`utils` -- contains utility functions and helpers
