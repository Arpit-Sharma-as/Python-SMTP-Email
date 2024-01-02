# Python SMTP Email

This Python script demonstrates sending emails using the Simple Mail Transfer Protocol (SMTP) through a Gmail account.

## Prerequisites

- Make sure you have a Gmail account.
- Enable "Less secure app access" in your Gmail account settings.
- Use an 'App password' for the script.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Arpit-Sharma-as/Python-SMTP-Email.git

Install the required Python libraries:
pip install secure-smtplib

Open the script (send_email.ipynb) and update the following variables:

email_address: Your Gmail email address
password: Your Gmail app password
subject: The subject of the email
body: The body of the email
recipient_emails: List of recipient email addresses

Run the script:
python send_email.ipynb

Check the specified recipient emails for the sent email.

Note

It is recommended to use environment variables or a configuration file for storing sensitive information like email and password.
