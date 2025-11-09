# Disposable Mailbox Service

A web-based disposable email service for temporary email addresses. This project provides secure and anonymous email communication with automatic expiration and inbox management.

## Overview

Disposable Mailbox is a lightweight web application that allows users to create temporary email addresses for one-time use or short-term communication. The service includes email forwarding, inbox management, and automatic expiration features to ensure privacy and security.

## Features

- **Temporary Email Addresses**: Generate disposable email addresses instantly
- **Email Forwarding**: Receive emails at temporary addresses
- **Inbox Management**: View and manage received emails
- **Automatic Expiration**: Emails automatically expire after a set period
- **Privacy-Focused**: No registration required, completely anonymous
- **Modern UI**: Clean, responsive interface built with Bootstrap

## Technologies Used

- **HTML5/CSS3**: Frontend structure and styling
- **JavaScript**: Client-side functionality
- **Bootstrap 5**: Responsive UI framework
- **Web APIs**: Email handling and management

## Project Structure

```
DisposableMailBox/
├── DisposableMailbox/
│   ├── assets/
│   │   ├── favicon.png
│   │   ├── scripts.js          # Main JavaScript functionality
│   │   └── styles.css          # Custom styles
│   ├── index.html              # Main application page
│   ├── list.txt                # Email list management
│   └── favicon.ico
└── README.md
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aryamanjalali/DisposableMailBox.git
cd DisposableMailBox
```

2. Open `DisposableMailbox/index.html` in a web browser

3. For production deployment, serve the files using a web server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

## Usage

1. Open the application in your web browser
2. Generate a new disposable email address
3. Use the address for temporary email needs
4. View received emails in the inbox
5. Emails automatically expire after the set time period

## Features in Detail

- **Email Generation**: Creates unique temporary email addresses
- **Real-time Updates**: Inbox updates in real-time
- **Email Viewing**: View full email content and headers
- **Auto-cleanup**: Automatic removal of expired emails

## Author

**Aryaman Jalali**
- GitHub: [@aryamanjalali](https://github.com/aryamanjalali)
- LinkedIn: [aryamanjalali](https://www.linkedin.com/in/aryamanjalali/)
- Email: aryamanj@bu.edu

## License

This project is for educational and research purposes.

## Acknowledgments

- Bootstrap team for the UI framework
- Open-source community for inspiration

