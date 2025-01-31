# Wamda - OTP Sending and Verification Platform

Wamda is a platform for sending and verifying OTP (One-Time Password) codes. This project provides a simple interface for users to request and verify OTPs.

## Features

- Send OTP to a specified phone number
- Verify the received OTP
- User-friendly interface with clear messages for success and failure
- Supports Arabic language and RTL (Right-to-Left) layout

## Deployment

The project is deployed and can be accessed at the following URL:
[https://m0ohannad.me/Wamda/](https://m0ohannad.me/Wamda/)


https://github.com/user-attachments/assets/d6045ca0-c020-4c98-8251-7a4dad930222



## Demo

### First Case: Successful OTP Sending via VendorA
In this case, the OTP is successfully sent via VendorA on the first attempt.
![First-Case](https://github.com/user-attachments/assets/d6045ca0-c020-4c98-8251-7a4dad930222)

### Second Case: OTP Sending Failure via VendorA and Automatic Switch to Another Vendor
In this case, the OTP sending fails via VendorA and automatically switches to another vendor to send the OTP successfully.
![Second-Case](https://github.com/user-attachments/assets/1b843895-d529-4d34-9d84-e0e87c6dc5a8)


## Getting Started

### Prerequisites

- A web browser
- Internet connection
- Clone and run the backend locally from this repository: [https://github.com/m0ohannad/otp-failover](https://github.com/m0ohannad/otp-failover)


### Usage

1. Open the [Wamda platform](https://m0ohannad.me/Wamda/).
2. Enter your phone number with the country code in the input field.
3. Click on the "إرسال OTP" button to send the OTP.
4. Enter the received OTP in the provided input field.
5. Click on the "تحقق من OTP" button to verify the OTP.

## Project Structure

### [`index.html`](index.html)

This file contains the HTML, CSS, and JavaScript code for the Wamda platform's user interface.

### `OTP Failover API.postman_collection.json`

This file contains the Postman collection for testing the OTP sending and verification API.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

Visit the deployed platform at [https://m0ohannad.me/Wamda/](https://m0ohannad.me/Wamda/) to try it out!

<!-- - Made with 💚 by [Mohannad Alhatame](https://m0ohannad.me) for Wamda 🚀 -->
