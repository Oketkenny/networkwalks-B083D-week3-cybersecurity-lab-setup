# networkwalks-B083D-week3-cybersecurity-lab-setup

Password Security Assessment: Hands-On with John the Ripper & Network Security Tools
This project documents a hands-on password security assessment conducted in a controlled cybersecurity lab environment.

The objective was to understand how password hashes can be assessed using John the Ripper (JtR) and how network security tools can be used to support password and authentication security testing.

The lab focused on:

Password hash identification
Hash cracking using John the Ripper
Wordlist-based password auditing
Brute-force/password recovery concepts
Network-based authentication assessment
Password security analysis
Interpreting cracking results
⚠️ Ethical Use Disclaimer:
All activities documented in this repository were performed against intentionally created test accounts, test hashes, and/or systems in an authorized laboratory environment. No unauthorized credentials, accounts, or third-party systems were targeted.
**Steps Followed**

Download John the Ripper from official website on your windows PC

Download Johnny GUI from official website

Run the setup file & install Johnny

open Johnny

Click on settings & browse

Select John.exe

Download the encrypted PDF file to your PC

Open the hash website & upload your pdf file to find its has 
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

Browse the PDF file & click on Upload

Select & copy the hash value

Paste the hash value inside notepad

Save as text file

Save the file with name hash1.txt

Open Johnny again

Click on ‘Open password file’

Browse to the hash1.txt file that you have just saved & click on Open

Click on ‘Start new attack’

Your PDF file password will be cracked (it might take some time depending on your computer
speed & password complexity)

Now you can use this password to open your PDF file

Open the encrypted PDF

Enter password1 (which you have just cracked)

Your PDF file will open.

<img width="872" height="317" alt="3 Password cracked" src="https://github.com/user-attachments/assets/766727ef-ee04-47dd-b87d-0e340d5dc2db" />


<img width="853" height="697" alt="Screenshot 2026-09-26 141648" src="https://github.com/user-attachments/assets/dca3a015-cd8a-434a-9184-266fc1929bfe" />


<img width="1065" height="845" alt="Screenshot 2026-09-26 140955" src="https://github.com/user-attachments/assets/5a77ed04-3139-45a7-8b2c-8073373641e2" />


<img width="586" height="666" alt="Screenshot 2026-09-26 141402" src="https://github.com/user-attachments/assets/f38ed6c7-7f4a-4811-9adc-cc8ed31f94ad" />



Task 2 Centers on using a network security tool by networkwalks
1. The Hash Calculator https://networkwalks.com/hash-calculator/
2. The Password Cracker  https://networkwalks.com/password-cracker/

   The hash calculator is used to calculate the hash of the encrypted pdf file

   The Hash is then copied and pasted to the password cracker that has a built-in word list.

   If the password is not found in the word-list, there is an option to upload a different word-list. Rockyou.txt was uploaded and used to resolve a password that wasn't found in the inbuilt worl-list.
   
<img width="1427" height="740" alt="Password Cracker 1" src="https://github.com/user-attachments/assets/b89bf71c-f182-4b7d-b404-14f2df2d7a32" />



<img width="882" height="255" alt="password cracker 3" src="https://github.com/user-attachments/assets/04b06250-85a4-4167-ac4a-14ed3c2676a1" />



<img width="997" height="742" alt="password cracker 2" src="https://github.com/user-attachments/assets/b6827e4c-b2cd-459e-ab0c-7d8cfc00c713" />




