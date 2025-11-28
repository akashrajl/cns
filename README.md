# Cryptography and Network Security Lab

This repository contains the source code and implementation details for the Cryptography and Network Security laboratory experiments. The projects cover classical encryption techniques, modern symmetric/asymmetric algorithms, hashing functions, and system security tools.

## 📂 Project Structure

The experiments are divided into three categories: Classical Encryption, Modern Security Standards, and System Security.

### 1. Classical Encryption Techniques (Java)
| File Name | Experiment Name | Description |
| :--- | :--- | :--- |
| `caesarCipher.java` | **Caesar Cipher** | A simple substitution technique shifting characters by a fixed offset `3`. |
| `playfairCipher.java` | **Playfair Cipher** | A digram substitution cipher using a 5x5 key matrix. |
| `hillCipher.java` | **Hill Cipher** | A polygraphic substitution cipher based on linear algebra (matrix multiplication). |
| `vigenereCipher.java` | **Vigenere Cipher** | A polyalphabetic substitution method using a repeating keyword. |
| `railFenceCipher.java` | **Rail Fence Cipher** | A transposition technique that writes message characters in a zigzag pattern. |
| `TransCipher.java` | **Row & Column Transformation** | A transposition cipher that rearranges the message based on column grids. |

### 2. Modern Security Standards (Java)
| File Name | Experiment Name | Description |
| :--- | :--- | :--- |
| `DES.java` | **DES Algorithm** | Implementation of the Data Encryption Standard using `DES/ECB/PKCS5Padding`. |
| `AES.java` | **AES Algorithm** | Advanced Encryption Standard example used for URL encryption. |
| `DiffieHellman.java` | **Diffie-Hellman Key Exchange** | Simulates the exchange of public/private keys to generate a shared secret. |
| `sha1.java` | **SHA-1 Algorithm** | Secure Hash Algorithm implementation to generate message digests. |
| `CreatingDigitalSignature.java`| **Digital Signature Standard** | Generates a digital signature for a text message using DSA. |

### 3. Web & System Security
| File Name | Experiment Name | Description |
| :--- | :--- | :--- |
| `rsa.html` | **RSA Algorithm** | Client-side implementation of Rivest-Shamir-Adleman encryption using HTML & JavaScript. |
| `Trojan.bat` | **Simple Trojan** | **(Warning)** A batch script demonstrating how malware loops processes to freeze a system. |

---

## 🛠️ Prerequisites

* **Java Development Kit (JDK):** Version 8 or higher is required to compile and run the `.java` files.
* **Web Browser:** Any modern browser (Chrome, Firefox, Edge) to run `rsa.html`.
* **Windows OS:** Required to run `Trojan.bat` and for the specific tool demonstrations (Snort/GMER) referenced in the lab manual.

---

## 🚀 How to Run

### Java Files
1.  Open your terminal or command prompt.
2.  Navigate to the directory containing the file.
3.  Compile the code:
    ```bash
    javac filename.java
    ```
4.  Run the class (ensure you use the main class name defined in the file):
    ```bash
    java filename
    ```

### RSA (HTML)
* Double-click `rsa.html` to open it in your default web browser.
* Enter two prime numbers (e.g., 53 and 59) and a message number to test the encryption logic.

### Trojan (Batch File) - ⚠️ CAUTION
* **Do not run `Trojan.bat` on a critical machine.**
* This script acts as a nuisance program that infinitely opens MSPaint, Notepad, CMD, and Explorer to simulate a Denial of Service.
* **To Stop:** You will likely need to restart your computer or rapidly kill the command processor in Task Manager.

---

## 🛡️ Additional Tools

The lab manual also references the following external tools for study:

1.  **Snort:** Open-source Network Intrusion Detection System (NIDS).
2.  **N-Stalker:** Web Application Security Scanner.
3.  **GMER / Rootkit Hunter:** Tools for detecting rootkits and hidden system processes.

---

## 📜 Disclaimer
This code is provided for **educational purposes only**. It is intended to demonstrate the logic behind cryptographic algorithms and malware behavior. The author is not responsible for any misuse of the provided code or tools.
