# CryptoAlgoJava
A collection of simple and educational cryptographic algorithms implemented in pure Java (no external libraries where possible). Perfect for learning and experimentation.

# JavaCryptoLab
[![Java](https://img.shields.io/badge/Language-Java%2011%2B-orange.svg)](https://www.oracle.com/java/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A collection of **simple, clean, and educational** implementations of classic cryptographic algorithms in Java.  
Intentionally kept minimal and easy to understand — great for students, beginners, or anyone who wants to see how crypto works under the hood without heavy frameworks.

## Currently Implemented Algorithms

| Algorithm              | Type                  | File                          | Notes                                 |
|------------------------|-----------------------|-------------------------------|---------------------------------------|
| LSRF                   | Stream cipher         | `LSRF.java`                   | Stream Block Encyption                |
| DES (simplified)       | Symmetric (Block)     | `SimpleDES.java`              | For learning purposes                 |
| AES (simple version)   | Symmetric (Block)     | `SimpleAES.java`              | Educational, not for production       |
| RSA                    | Asymmetric            | `RSA.java`                    | Key generation + encrypt/decrypt      |
Coming SOON !
| Caesar Cipher          | Symmetric             | `CaesarCipher.java`           | Classic shift cipher                  |
| Vigenère Cipher        | Symmetric             | `VigenereCipher.java`         | Poly-alphabetic substitution          |
| Diffie-Hellman         | Key Exchange          | `DiffieHellman.java`          | Simple demo with small primes         |
| SHA-256                | Hash Function         | `SHA256.java`                 | From scratch implementation           |
| MD5                    | Hash Function         | `MD5.java`                    | Pure Java, educational only           |

*(Add or remove rows as you actually have the files)*

## Why this repository exists
- Learn how cryptographic primitives actually work
- No external dependencies (pure Java)
- Short, readable, and heavily commented code
- Great starting point for university assignments or personal study

## Requirements
- Java 11 or higher
- Just clone and run! No build tools required for most examples.

## How to run an example
```bash
git clone https://github.com/your-username/JavaCryptoLab.git
cd JavaCryptoLab

# Example: Run RSA demo
javac RSA.java
java RSA
