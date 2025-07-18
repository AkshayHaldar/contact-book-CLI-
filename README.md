# Contact Book

## Overview
Contact Book is a simple command-line application written in Python that helps you manage your contacts efficiently. You can add, delete, view individual contacts, or list all contacts. The contacts are saved persistently in a file, so your data is preserved between sessions.

## Features
- Add new contacts with name and phone number
- Delete existing contacts by name
- View phone number of a specific contact
- List all saved contacts
- Persistent storage of contacts in a file (`contact.txt`)

## Prerequisites
- Python 3.x installed on your system

## Installation
No installation required. 
Simply download the `contact.py` file.

## Usage
Run the program from your command line or terminal:
```
python contact.py
```

Upon first run, if no contacts file is found, you will be prompted to enter initial contacts.

### Available Operations
- `add`: Add a new contact  
  You will be prompted to enter the contact's name and phone number.

- `delete`: Delete an existing contact  
  You will be prompted to enter the contact's name to delete.

- `view`: View a specific contact's phone number  
  You will be prompted to enter the contact's name to view.

- `view_all`: List all contacts currently saved.

- `exit`: Save all contacts to file and exit the program.

## Data Persistence
Contacts are saved in a file named `contact.txt` located in the same directory as the script. The program automatically loads contacts from this file on startup and saves them on exit.

## Error Handling
- If you enter an invalid number of contacts during initial setup, the program will notify you and prompt again.
- If you try to delete or view a contact that does not exist, you will be informed accordingly.
- if you think there must be more error handling make a issue
- or you can fork this repo and contribute 

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

