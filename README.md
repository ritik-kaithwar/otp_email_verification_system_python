# OTP Email Verification System

A Python-based OTP (One-Time Password) verification system that generates, sends, and validates a 6-digit OTP via email. Ideal for learning about authentication systems and securely handling email communications in Python.

---

## Features

- Random 6-digit OTP generation
- OTP sent to user email via SMTP
- OTP input validation loop
- Demonstrates secure email-based authentication

---

## How It Works

1. Generates a random 6-digit OTP using Python's `random` module.
2. Sends the OTP via Gmail SMTP using `smtplib` and `email.mime`.
3. Prompts the user to input the OTP.
4. Validates the OTP input and loops until the correct one is entered.

---

## Requirements

- Python 3.x
- Gmail account with **App Password** enabled

> No external libraries required — uses built-in Python modules only.

---

## Dependencies

- `random`
- `smtplib`
- `email.mime`

---

## Setup & Usage

1. Install Python (or use Jupyter Notebook/Google Colab).
2. Save the code in a `.py` or `.ipynb` file.
3. Run the script:
   - For Python file: `python otp_verification.py`
   - For Notebook: Run all cells
4. Enter your email and the OTP you receive.
5. Validate OTP and proceed.

---

## Test Scenarios

| Scenario                  | Expected Behavior         |
|---------------------------|---------------------------|
|  Correct OTP             | Access Granted            |
|  Incorrect OTP           | Re-prompts for OTP input  |
|  Multiple wrong inputs   | Loops until correct input |

---

## Learning Objectives

- Securely send emails via Python
- Handle OTP-based authentication
- Real-world application of built-in libraries