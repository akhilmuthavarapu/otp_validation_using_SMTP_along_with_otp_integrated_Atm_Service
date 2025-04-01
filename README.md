# otp_validation_using_SMTP_along_with_otp_integrated_Atm_Service
# 🔐 OTP Verification via Email (Integrated with ATM System) 🏦

## 📌 Overview
This Python script generates and sends a **One-Time Password (OTP)** via email for verification purposes. The OTP validation system is integrated into a **console-based ATM project**, ensuring secure authentication for banking operations.

## 🚀 Features
✅ Generates a **4-digit OTP**.
✅ Sends OTP via **Gmail SMTP protocol**.
✅ Supports OTP verification for **secure banking authentication**.
✅ Enables **PIN generation and reset** using OTP.
✅ Allows **OTP-based login** for accounts without a PIN.
✅ Supports sending OTPs to **single or multiple email addresses**.

## 🔧 Prerequisites
Ensure you have the following installed:
🔹 **Python 3.x**
🔹 Required Python modules:
   - `smtplib` 📩
   - `random` 🎲
   - `email.mime.multipart` 📜
   - `email.mime.text` ✉️

## ⚙️ Setup and Configuration
1️⃣ Enable **Less Secure Apps Access** or create an **App Password** in your Gmail account.
2️⃣ Replace `YOUR_GOOGLE_PASSKEY` with your actual **Google App Password** in the script.
3️⃣ Update the sender's email address (`akhilmuthavarapu1@gmail.com`) if necessary.

## 🎯 Usage
1️⃣ Run the ATM script:
   ```bash
   python atm_script.py
   ```
2️⃣ Choose an operation:
   - 💰 **Withdraw**
   - 💵 **Deposit**
   - 🔑 **PIN Generation/Reset**
   - 📄 **Mini Statement**
   - 🔄 **Transaction History**
3️⃣ If an account **does not have a PIN**, an OTP will be sent to the **registered email** for verification.
4️⃣ Enter the **received OTP** for authentication.
5️⃣ Proceed with the selected **ATM operation**.

## 🔗 Integration with ATM System
🔹 **otp(receiver)**: Generates an OTP, sends it via email, and verifies it.
🔹 **otp_valid()**: Used in the ATM system to authenticate users **without a PIN**.
🔹 **userchoice()**: Provides an option to send OTPs to a **single or multiple recipients**.
🔹 **ATM Functionalities**:
   - 🏦 Users can **withdraw** and **deposit** money.
   - 🔑 Users can **generate/reset their PIN** using OTP authentication.
   - 📄 Users can **view their mini statement** and **transaction history**.

## 🔒 Security Considerations
⚠️ Never hardcode your **email password** in the script. Use **environment variables** or a **secure credential manager**.
⚠️ Implement **rate-limiting** to prevent **misuse**.
⚠️ Ensure **SMTP access** is **secured and restricted**.

## ⚠️ Disclaimer
Use this script **responsibly**. The author is **not liable** for any **misuse or security breaches**.

---
👨‍💻 **Author:** Venkata Akhil Muthavarapu



