# Encryption Techniques 
## Learning Objectives 
- Understand cryptography basics 
- Differenciate between symmetric and asymmetric encryption 
- Learn hasing and digital signature concepts 

## cryptography 
cryptography is a technique of securing information and communication using codes to ensure confidentiality , intergrity and Authentication

## Symmetric Encription 
- Uses one key for both encryption and decryption.
- Fast , suitable for bulk data encryption .

##Asymmetric Encryption
- Uses two keys: public key (for encryption) and private key (for descyption)
- Used for secure key exchange and digital communication 

## Hashing
- coverts data into a fixed-length string.
- Used for secure data integrity verification 
- One-way process - cannot be reversed
- Used for password storage and integrity checking.
- Common Algorithms: SHA-256, MD5 (deprecated)

## Digital Signatures and Certificates
- Ensure authenticity and non-repudiation.
- A digital signature uses private key to sign data and public key to verify.
- Certificates (X.509) are issued by Certificate Authorities (CAs) for trust verification (used in HTTPS).

## Examlpes
 When visiting https://www.federalbank.co.in/
- brower verifies certificate signed by CA to ensure authenticity.
