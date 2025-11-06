# Cryptography-Signature-Simulation
A simulation comparing RSA and ElGamal digital signatures, with a web-based demo of a secure messenger.

This project, built for the Cryptography and Network Security course (BECE411L), provides a comprehensive analysis and simulation of RSA and ElGamal digital signature algorithms.

## Project Components

This repository contains three main parts:

1.  **Python Performance Simulation:** A Python script (in a Colab notebook) that performs a head-to-head comparison of RSA and ElGamal, measuring key generation, signing, and verification times.
2.  **Interactive Secure Messenger:** A `secure_messenger.html` file that provides a live, visual demonstration of a complete secure communication system (encryption + digital signature).
3.  **Review 2 Presentation:** The final presentation slides summarizing the project's goals, methodology, and findings.

## Part 1: Performance Comparison (RSA vs. ElGamal)

This simulation compares the two algorithms at a 1024-bit key size.

### Key Findings:
* **Speed:** RSA was found to be significantly faster in key generation and verification.
* **Efficiency:** RSA produced a signature that was half the size of ElGamal's (128 bytes vs. 256 bytes).

![Performance Charts](images/your-chart-image.png)
*(To make this work, you'd need to create an `images` folder and upload screenshots of your charts)*

## Part 2: Interactive Secure Messenger Demo

`secure_messenger.html` is a self-contained web application that simulates a secure chat between "Alice" and "Bob," implementing our full flowchart.

### Features:
* **Confidentiality:** Messages are encrypted using RSA.
* **Authenticity & Integrity:** Messages are digitally signed to prove the sender's identity and ensure the message is not tampered with.
* **Attack Simulation:** A "Tamper!" button is included to simulate a man-in-the-middle attack and prove that the system can detect and reject corrupted messages.

### How to Run:
1.  Download the `secure_messenger.html` file.
2.  Open it in any modern web browser (like Chrome or Firefox).

---
*A project by Ansu Raj, Astitva Sharma, Sanidhya Saxena, Satyam Saurav, and Dhruv Jaipuria for Vellore Institute of Technology, Vellore.*
