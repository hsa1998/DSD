# DSD

This Python application automates the processing of purchase order emails and extracts key information for order fulfillment.

## Features:

1. Reads specific emails containing purchase orders.
2. Extracts data and attached PDFs from purchase order emails.
3. Parses PDF attachments to extract order details.
4. Logs extracted details to a SQLite database.
5. Identifies unfulfilled orders and generates reminder emails for a delivery system.

## Getting Started
Prerequisites:
Python 3.12

## Libraries:
- imaplib (for interacting with email server)
- PyPDF2 (for parsing PDF attachments)
- sqlite3 (for interacting with SQLite database)
- time (for handling timestamps)
- base64 (for decoding email attachments)
- os (for potential file path operations)
- smtplib (for sending reminder emails)

## Links
- Python imaplib documentation: https://docs.python.org/3/library/imaplib.html
- PyPDF2 documentation: https://pypdf2.readthedocs.io/
- SQLite documentation: https://www.sqlite.org/
- Python time documentation: https://docs.python.org/3/library/time.html
- Python base64 documentation: https://docs.python.org/3/library/base64.html
- Python os documentation: https://docs.python.org/3/library/os.html
- Python smtplib documentation: https://docs.python.org/3/library/smtplib.html

## Authors/Maintainers
Haseeb Afridi