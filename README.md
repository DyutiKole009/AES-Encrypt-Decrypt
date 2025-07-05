# AES-Encrypt-Decrypt

This project implements **AES (Advanced Encryption Standard)** encryption in C++. It demonstrates how to securely encrypt plaintext data and decrypt ciphertext using a symmetric key encryption algorithm.

## 📁 Files

- `AES.cpp` - Core implementation of AES encryption.
- `README.md` - Project documentation.

## 🚀 Features

- AES 128-bit encryption and decryption
- Used Rijndael algorithm with look-up tables 
- Byte substitution (S-box), shift rows, mix columns, and add round key operations
- Same code can be used for decryption as well
- Easily modifiable for other AES variants (192/256-bit)

## 🛠️ How to Compile and Run

### Requirements

- A C++ compiler (e.g., `g++`)
- C++11 or higher (if required)

### Compilation

```bash
g++ AES.cpp -o aes
```

### Run

```bash
g++ AES.cpp -o aes
```
