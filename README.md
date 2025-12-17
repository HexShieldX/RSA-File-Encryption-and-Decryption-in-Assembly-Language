**RSA File Encryption/Decryption**
**Overview**
This project is a console-based RSA encryption and decryption tool implemented in x86 Assembly (MASM) using Irvine32 library.
It allows users to encrypt and decrypt files using RSA with pre-defined keys. This project demonstrates cryptography concepts, modular assembly coding, file handling, and console I/O.

**Features**
1.Encrypts files using RSA algorithm (C = M^e mod n)
2.Decrypts files (M = C^d mod n)
3.Handles file input/output efficiently
4.Interactive console menu to select encryption or decryption
5.Outputs encrypted/decrypted data to output.txt
6.Modular design using procedures for RSA exponentiation, file handling, and console I/O

**Keys Used**
| Parameter | Value |
| --------- | ----- |
| n         | 3233  |
| e         | 17    |
| d         | 2753  |
Note: Keys are hard-coded for demonstration; can be extended to use dynamic key generation.

**Requirements**
1.MASM assembler / Visual Studio 2022 with MASM support
2.Irvine32 library

**How to Run**

Assemble the code in MASM/Visual Studio.
Open command prompt and navigate to the compiled .exe.
Run the program with the input file as a command-line argumen
Select mode:
1.Press 1 to Encrypt
2. Press 2 to Decrypt
Encrypted/decrypted output will be saved to output.txt.

**Code Structure**
1.Main Procedure: Handles file reading, menu, encryption/decryption flow
2.ModExp Procedure: Performs modular exponentiation (Base^Exp mod n)
3.File Handling Procedures: Open, read, write, close files
4.Console I/O Procedures: Display messages and read user input

**Output Sample**
1. ENCRYPTION
Input: hello.txt
Command: RSA_Encryption.exe hello.txt
Mode: 1
Output: output.txt (encrypted content)

2.DECRYPTION
Input: output.txt
Command: RSA_Encryption.exe output.txt
Mode: 2
Output: decrypted.txt (original content)

**License**

This project is licensed under the MIT License – see the LICENSE
 file for details.

**Author**
Arshman Abbas – Student, Air University Islamabad







