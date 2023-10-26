# OCR Code Challenges
This is a repository of all code challenges recommended by OCR.
Below are the descriptions of each program:
# Descriptions
## Caesar Cipher

### Summary

The Caesar Cipher program implements the following features:
 - Graphical Interface
 - Encryption and decryption
 - User choice of phrase and key
 - Robust design to minimalise errors and improve user experience
 - Brute-force attack system with a dictionary lookup feature for possible matches
 - Saving of encryption and decryption results in a text file

### Requirements and Running

#### ONLINE ####
To run this program online, use the following link to the project Repl:

```
https://replit.com/@pmkhambhaita/Caesar-Cipher
```

#### OFFLINE ####

To run this program offline, the following are required:
 - Python 3.x
 - Tkinter library
 - ~ 8MB free space

In a terminal, enter the directory of the program and type:

```bash
python3 main.py
```

### Usage

A GUI window will open upon running. There are 3 main elements to the GUI - the entry box where a message is entered, and the two buttons for encrypting and decrypting.
#### To encrypt:
  - Enter the message you wish to encrypt in the text box
  - Press the "Encrypt" button
  - 

### About the caesar_cipher function

The caesar_cipher itself is much shorter than expected, due to the use of an ASCII system rather than an alphanumeric system. I utilised the fact that letters are represented by ascending ASCII numbers (lowercase a being 001 and so on). By using this, you can simply add the key to the ASCII representation of each letter and convert back into alphanumeric characters. This allows for a much shorter program, as well as more versatility surrounding the characters on which the cipher is applied, as it is a short matter to exclude all non-alpha characters, which enables for much longer strings to be used. 


Any questions/bugs, please raise an issue!

Galileo
