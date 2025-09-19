AES Encryption Terminal 🛡️
A sleek, terminal-themed web application for encrypting and decrypting text using the industry-standard AES (Advanced Encryption Standard) algorithm. This tool provides a secure, client-side interface for protecting sensitive information, with the added ability to save and manage encrypted messages directly in the browser.

Live Demo -> https://aes-encryptions.netlify.app/



✨ Features
Strong Encryption: Utilizes the robust AES algorithm via the CryptoJS library for secure text encryption.

Client-Side Security: All encryption and decryption processes happen locally in your browser. Your password and plaintext are never sent to any server.

Save & Load Messages: Store your encrypted ciphertexts in local storage with a custom tag for easy retrieval.

Responsive Design: A clean and functional interface that works seamlessly on both desktop and mobile devices.

Themed UI: A cool "hacker terminal" aesthetic that makes securing your data feel more engaging.

Clipboard Integration: Easily copy the encrypted or decrypted text to your clipboard with a single click.




💻 Tech Stack
HTML5: For the core structure and content of the application.

CSS3: For custom styling, animations, and the responsive terminal theme.

JavaScript (ES6+): For all the application logic, including DOM manipulation and event handling.

CryptoJS Library: A powerful JavaScript library of cryptographic standards, used here for the AES implementation.




🚀 Getting Started
To run this project on your local machine, follow these simple steps.

Clone the repository

Navigate to the project directory

Open in browser:
Simply open the index.html file in your favorite web browser. No special server or dependencies are required




🛠️ How to Use
To Encrypt:

Enter the text you want to secure in the Input_Text field.

Type a strong, secret password into the Secret_Key field.

Click the [ Encrypt ] button. The resulting encrypted ciphertext will appear in the Output_Log.

To Decrypt:

Paste the previously encrypted ciphertext into the Input_Text field.

Enter the exact same password you used to encrypt it.

Click the [ Decrypt ] button. The original plaintext will be revealed in the Output_Log.

To Save a Message:

After encrypting text, enter a memorable name in the Enter a tag... field.

Click the [ Save ] button. Your encrypted message is now saved.

To Load a Message:

Click the dropdown menu (> Select saved data...).

Choose the tag of the message you want to load. The encrypted ciphertext will automatically be placed in the Input_Text field, ready for decryption.




📄 License

Copyright (c) 2025 Tasis Alwaz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
