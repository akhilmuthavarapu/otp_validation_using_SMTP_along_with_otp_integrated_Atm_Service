# otp_validation_using_SMTP_along_with_otp_integrated_Atm_Service
# OTP Verification via Email

## Overview
This Python script generates and sends a One-Time Password (OTP) via email for verification purposes. The user can send the OTP to a single recipient or multiple recipients at once.

## Features
- Generates a 4-digit OTP.
- Sends OTP via Gmail using the SMTP protocol.
- Allows OTP verification by the recipient.
- Supports sending OTPs to single or multiple email addresses.

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python modules:
  - `smtplib`
  - `random`
  - `email.mime.multipart`
  - `email.mime.text`

## Setup and Configuration
1. Enable **Less Secure Apps Access** or create an **App Password** in your Gmail account.
2. Replace `YOUR_GOOGLE_PASSKEY` with your actual Google App Password in the script.
3. Update the sender's email address (`akhilmuthavarapu1@gmail.com`) if necessary.

## Usage
1. Run the script:
   ```bash
   python script_name.py
   ```
2. Choose whether to send the OTP to a single recipient or multiple recipients.
3. Enter the recipient email address(es).
4. The recipient(s) will receive an OTP via email.
5. Enter the received OTP in the terminal for verification.

## Code Breakdown
- **otp(receiver)**: Generates an OTP, sends it via email, and verifies it.
- **userchoice()**: Provides an option to send OTPs to a single or multiple recipients.

## Security Considerations
- Never hardcode your email password in the script. Use environment variables or a secure credential manager.
- Consider implementing rate-limiting to prevent misuse.
- Ensure SMTP access is secured and restricted.

## Disclaimer
Use this script responsibly. The author is not liable for any misuse or security breaches.

---
**Author:** Akhil Muthavarapu

