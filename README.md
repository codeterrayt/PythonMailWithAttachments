# 📧 Python Mail with Attachments

Send emails with attachments using Python's `smtplib` and the `email` library. This simple script demonstrates how to send emails with attachments programmatically.

## Introduction

This PythonMailWithAttachments project allows you to send emails with attachments using Python. It uses the `smtplib` library to establish an SMTP connection and the `email` library to create and format the email message. This script is particularly useful for sending automated emails with attachments.

## Features

- **Attachment Support:** Attach files to your emails with ease.
- **Easy Configuration:** Set up sender's email, password, receiver's email, and other details in the script.
- **Customizable Message:** Personalize the email body as needed.

## Prerequisites

Ensure you have Python installed on your system.

## Installation

1. Clone the GitHub repository:

    ```bash
    git clone https://github.com/codeterrayt/PythonMailWithAttachments.git
    cd PythonMailWithAttachments
    ```

2. Install the required libraries:

    ```bash
    pip install secure-smtplib
    ```

## Usage

1. Open `main.py` in a text editor.

2. Update the following variables with your email details:
    - `fromaddr`: Sender's email address.
    - `password`: Sender's email password.
    - `toaddr`: Receiver's email address.
    - `subject`: Email subject.
    - `body`: Email body text.
    - `filename`: Name of the file to be attached (e.g., "home.png").

3. Save the changes.

4. Run the script:
    ```bash
    python main.py
    ```

5. The script will prompt you for your email password and send the email with the attached file.

## Development

Feel free to explore and modify the code to suit your specific needs. You can customize the email subject, body, and attachment details as per your requirements.

## Acknowledgments

This project uses the `smtplib` and `email` libraries for sending emails with attachments. Explore the [Python `smtplib` Documentation](https://docs.python.org/3/library/smtplib.html) and [Python `email` Documentation](https://docs.python.org/3/library/email.html) for more information.

💌 Happy Emailing! 🚀
