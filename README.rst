# Password Strength Analyzer using Machine Learning

## Project Overview
Weak passwords are one of the most common causes of security breaches.  
This project implements a password strength analyzer that evaluates the security level of a password and estimates how difficult it would be for an attacker to guess it.

The goal is to provide feedback to users so they can create stronger and more secure passwords.

---

## Features

- Evaluates password strength from **Very Weak to Strong**
- Estimates password cracking difficulty
- Detects common patterns such as:
  - dictionary words
  - personal information
  - predictable character sequences
- Provides suggestions for improving password security

---

## Methodology

The system evaluates passwords using several techniques:

### Pattern Detection
Identifies predictable password patterns such as:

- common dictionary words
- repeated characters
- keyboard sequences

### Entropy Estimation
Calculates password complexity based on:

- length
- character variety
- randomness

### Password Guessing Estimation
Estimates the number of guesses required to crack the password in different attack scenarios.

---

## Implementation

The project is implemented in Python and includes:

- password strength evaluation functions
- pattern detection algorithms
- password feedback generation

Example usage:

```python
from password_strength_analyzer import analyze_password

password = "ExamplePassword123"
result = analyze_password(password)

print(result)


## Author
Atharv Patil
