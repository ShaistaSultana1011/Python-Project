🔐 OTP Verification System using Python


A simple Python script that generates a 6-digit OTP (One Time Password) and sends it via email for user verification. This is useful for implementing basic security validation systems in registration/login workflows.


🚀 Features

Generates a 6-digit numeric OTP

Sends OTP to any valid email using Gmail SMTP

Verifies user input against the generated OTP

Simple and beginner-friendly script written in Python

🛠 Tools & Libraries Used

Tool/Library	Purpose

random	- For generating random digits
math	- For flooring random numbers
smtplib	- For sending emails via SMTP
input()	- To take user email and OTP input

🧪 How It Works

A 6-digit OTP is generated using Python's random module.

The script sends the OTP to the user's email using Gmail's SMTP server.

The user is prompted to enter the received OTP.

If the input matches the generated OTP, verification is successful.

📌 Prerequisites

Python installed (preferably 3.x)

A Gmail account with App Password enabled (for login via SMTP)

Allow "Less secure apps" or use App Passwords if 2FA is enabled

🔐 Setup Gmail for SMTP
Go to Google Account Security

Enable 2-Step Verification

Under "App passwords", generate a password.

