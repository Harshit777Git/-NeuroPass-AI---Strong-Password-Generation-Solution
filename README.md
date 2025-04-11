# 🔐 NeuroPass AI - Strong Password Generation Solution  
**By Harshit Shetty**  
*Part of NeuroForge - Next-Gen AI-Solutions*


[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)  
[![Java](https://img.shields.io/badge/Java-17%2B-red)](https://java.com)

# -NeuroPass-AI---Strong-Password-Generation-Solution
This project is a Java Console Application to generate random passwords and perform password strength checks.


## 🚀 Features -integration planned Q2 2026
- AI-Ready Architecture (GAN integration)  
- Military-Grade Entropy (128-bit+)  
- NIST 800-63B Compliant  

## 📦 Installation  
```bash
git clone https://github.com/Hash777/HashPassword-Generator.git
cd HashPassword-Generator/Password-Generator
javac src/*.java -d out/production/Password-Generator# Password-Generator

## Current Functionalities

### 1. Generating a Password:

- The user answers with "Yes" or "No" to questions about using uppercase letters, lowercase letters, numbers, or symbols.
- The user then enters the desired length of the password.
- A password alphabet is generated based on the user's answers, which is a string containing the chosen characters.
- Random characters from the password alphabet are selected and combined to form a completely random string according to the user's preferences.
- The randomly generated password is then displayed on the console.

### 2. Checking a Password's Strength:

The strength check is based on the following criteria:
- The password uses uppercase letters.
- The password uses lowercase letters.
- The password uses numbers.
- The password uses symbols.
- The length of the password is 8 or more (8 is often the minimum required length for a decent password).
- The length of the password is 16 or more (16 is considered to be the minimum length for a good password).

These criteria are used to calculate a score for the password, which determines the message displayed to the user indicating the strength of the password (weak/medium/good/great).

### 3. Displaying Useful Information:

This is a minor feature that displays information for the user on the console about password security, such as avoiding using the same password twice, avoiding character repetition, keyboard patterns, dictionary words, letter or number sequences, etc.

### 4. QUIT
