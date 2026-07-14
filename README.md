# File Encryption and Decryption using Python

## 📌 Project Overview

This project demonstrates how to securely encrypt and decrypt a file using Python's **Cryptography (Fernet)** library.

The program:
- Generates a secret encryption key.
- Stores the key in a file (`mykey.key`).
- Encrypts a CSV file (`grades.csv`).
- Saves the encrypted data as `enc_grades.csv`.
- Decrypts the encrypted file.
- Saves the decrypted data as `decrypted_grades.csv`.

This project is useful for learning basic **file encryption**, **symmetric key cryptography**, and **secure file handling** in Python.

---

## 📂 Project Structure

```
project/
│── encrypt&decrypt.py
│── grades.csv
│── mykey.key               (Generated automatically)
│── enc_grades.csv          (Generated automatically)
│── decrypted_grades.csv    (Generated automatically)
│── README.md
```

---

## ⚙️ Requirements

- Python 3.x
- Cryptography library

Install the required package:

```bash
pip install cryptography
```

or

```bash
python -m pip install cryptography
```

---

## ▶️ How to Run

Run the program using:

```bash
python encrypt&decrypt.py
```

or

```bash
python3 encrypt&decrypt.py
```

---

## 🔄 Workflow

1. Generate a secret encryption key.
2. Save the key as `mykey.key`.
3. Read the original file (`grades.csv`).
4. Encrypt the file.
5. Save the encrypted file as `enc_grades.csv`.
6. Read the encrypted file.
7. Decrypt the data using the same key.
8. Save the decrypted file as `decrypted_grades.csv`.

---

## 📁 Output Files

| File | Description |
|------|-------------|
| `grades.csv` | Original file |
| `mykey.key` | Secret encryption key |
| `enc_grades.csv` | Encrypted file |
| `decrypted_grades.csv` | Decrypted file |

---

## 🔒 Technologies Used

- Python
- Cryptography (Fernet)

---

## 📖 Learning Objectives

- Understand symmetric encryption.
- Learn how to generate and store encryption keys.
- Encrypt and decrypt files using the Fernet algorithm.
- Work with binary files in Python.

---

## 👨‍💻 Author

**S. Md. Nihaal**

Cyber Security & Python Learning Project

---
