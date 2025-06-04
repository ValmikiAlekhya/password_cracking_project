Password Cracking Project Summary
---------------------------------

Project Overview:
This project demonstrates the process of cracking MD5 hashed passwords using the tool John the Ripper. The objective was to successfully recover plaintext passwords from their hashed forms.

Tools Used:
- John the Ripper (john.exe)

Input:
- A file named "hashes1.txt" containing MD5 hashes of passwords.

Process:
1. The hashes were stored in the "hashes1.txt" file.
2. John the Ripper was run using the command:
   john.exe --show --format=raw-md5 hashes1.txt
3. The tool processed the hashes and attempted to crack them using its default wordlists and rules.
4. Successfully cracked passwords were displayed alongside their corresponding hashes.

Output:
- The MD5 hash "34819d7beeabb9260a5c854bc85b3e44" was cracked and revealed the password: "password".
- The command output confirmed that 1 password hash was cracked with 0 remaining.

Conclusion:
This project illustrates the vulnerability of MD5 hashes to password cracking tools like John the Ripper. It emphasizes the need for stronger hashing algorithms and security practices to protect password data.

---

Prepared by: Valmiki Alekhya 
Date: 04-06-2025
