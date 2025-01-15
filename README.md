# OTP Verification System with Flask

This project implements a simple OTP (One-Time Password) verification system using **Flask** and **Gmail** for email delivery. Users log in with their email, receive an OTP, and verify it to proceed. The login page includes fields for a **username**, **password**, and **email** to simulate user authentication (which can be extended to integrate a database in the future).

## Features

- **Login Form**: Accepts username, password, and email.
- **OTP Generation**: Generates a random 6-digit OTP.
- **Email Delivery**: Sends OTP to the provided email address using Gmail SMTP.
- **OTP Verification**: User can verify the OTP to log in.
- **Tailwind CSS Styling**: Beautiful and responsive frontend design.

## Prerequisites

- Python 3.7+ 
- Gmail account for sending OTP emails (you can use an app password for secure login).
- Flask library

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/otp-verification-flask.git
   cd otp-verification-flask
