Cipher Wheel Encryption/Decryption Tool
Overview
The Cipher Wheel Encryption/Decryption Tool is a simple implementation of the substitution cipher algorithm using JavaScript, HTML, and CSS. This tool replaces each letter in the plaintext with a letter a certain number of positions down the alphabet, making it a fun and educational project for demonstrating encryption and decryption concepts.

Usage
To use the Cipher Wheel Encryption/Decryption Tool, follow these steps:

Clone the repository or download the source code.
Open the index.html file in a web browser.
Select the desired operation from the "Encrypt" or "Decrypt" radio button.
Enter the desired shift value, which determines how many positions each letter will be shifted.
Enter the desired modulo value, which determines the length of the alphabet.
Select the letter case you want to maintain (original case, lowercase, or uppercase).
Select the foreign key you want to ignore or remove. If you select to remove it, symbols will be removed.
Enter the text you want to encrypt or decrypt in the input field provided.
Click the submit button.
The result will be displayed in the output section.
Examples
Encryption
If you want to encrypt the message "HELLO" with a shift of 3, the resulting ciphertext will be "KHOOR".

Decryption
To decrypt the ciphertext "KHOOR" with a shift of 3, the original plaintext "HELLO" will be recovered.

Files
The project consists of the following files:

index.html: The HTML file containing the user interface and JavaScript code.
style.css: The CSS file for styling the user interface.
script.js: The JavaScript file containing the implementation of the Cipher Wheel algorithm.
README.md: The readme file with instructions and information about the project.
Compatibility
This Cipher Wheel Encryption/Decryption Tool should work on most modern web browsers that support JavaScript. No additional libraries or frameworks are required.

Acknowledgments
This project was inspired by the concept of the substitution cipher and was created for educational purposes.