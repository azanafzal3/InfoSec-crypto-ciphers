
# 🔐 Assignment 2 – Symmetric Encryption and Stream Ciphers

This repository contains our implementation and analysis for **Assignment 2** of the **Information Security** course (Spring 2025 – 6th Semester).  
The assignment is divided into two major parts:

---

## 📦 Part 1: Block Cipher (SEED Lab – Secret-Key Encryption)

Based on the [SEED Labs Crypto Encryption Lab](https://seedsecuritylabs.org/Labs_20.04/Crypto/Crypto_Encryption/), this section includes:

- Frequency analysis on substitution ciphers
- Encryption using various block cipher modes (AES, Blowfish, etc.)
- ECB vs CBC image encryption visualization
- Padding behavior in various modes
- Error propagation in encrypted ciphertexts
- Initial Vector (IV) behavior and common mistakes

---

## 🔁 Part 2: Stream Cipher – LFSR & Synchronous Stream Cipher

This section includes:

- **LFSR Simulator**: Python implementation for sequence generation based on user-defined feedback polynomials
- **Key Stream Analysis**:
  - Sequence generation for primitive, irreducible, and reducible polynomials
  - Polynomial classification and sequence visualization
- **Custom Stream Cipher**:
  - Encrypts ASCII using LFSR-generated key stream
  - Performs a plaintext attack to infer the feedback polynomial

---

## 🧪 Libraries Used

```python
import numpy as np
import random
import matplotlib.pyplot as plt
```

---

## ▶️ How to Run

Make sure Python 3 is installed, then run the respective scripts:

```bash
python StreamCipher-PartA01.py       
python StreamCipher-PartA02-any3.py      
python StreamCipher-PartB.py       
```

---

## 🏫 Academic Info

- **Course**: Information Security
- **Semester**: 6th Semester, Spring 2025
- **Duration**: April – May 2025
- **Assignment**: Assignment 2 – Block and Stream Cipher Implementation

---

## 📘 License & Attribution

This project includes work based on **SEED Labs** by Wenliang Du, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
