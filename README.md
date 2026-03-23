#Cryptography Project - Kali Linux CLI Implementation

##Overview
A complete hands-on implementation of four fundamental cryptographic techniques using only command-line tools available in Kali Linux. This project was completed as part of a cybersecurity certificate programme.

##Project Modules

### Module 1 — Symmetric Encryption (AES-256-CBC)
- Tool: OpenSSL
- Encrypted and decrypted files using a shared password
- Implemented PBKDF2 key derivation for password strengthening

### Module 2 — Asymmetric Encryption (RSA-2048)
- Tool: OpenSSL
- Generated RSA public and private key pairs
- Encrypted messages with public key, decrypted with private key

### Module 3 — Cryptographic Hashing (SHA256 & MD5)
- Tools: sha256sum, md5sum
- Generated file fingerprints using SHA256 and MD5
- Demonstrated the avalanche effect
- Verified file integrity and detected tampering

### Module 4 — Steganography (LSB Embedding)
- Tool: Stegosuite
- Concealed secret messages inside image files
- Extracted hidden messages from steganographic images
- Implemented dual-layer protection: encryption + steganography

## Tools Used
- Kali Linux (operating system)
- OpenSSL (encryption and key management)
- sha256sum / md5sum (hashing and integrity)
- Stegosuite (steganography)

## Skills Demonstrated
- Symmetric and asymmetric cryptography
- Key generation and management
- File integrity verification
- Information hiding techniques
- Command-line tool proficiency
- Security analysis and documentation

## Academic Report
A full academic report documenting the theoretical foundations, implementations, security analysis, and APA 7th edition references is included in this repository.

## Author
Julius Kariuki
March 2026


## License
MIT License
