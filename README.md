# URL to QR Code Generator

## Description

This Node.js application converts a user-entered URL into a QR code image and saves the URL into a text file. It uses the `inquirer` package to prompt the user for input, the `qr-image` package to generate the QR code, and Node's native `fs` module to handle file operations.

## Features

- Prompt the user for a URL.
- Generate a QR code image from the provided URL.
- Save the QR code image as `qr_img.png`.
- Save the provided URL into a text file named `url.txt`.

## Prerequisites

Ensure you have Node.js installed. You can download it from [here](https://nodejs.org/).

## Installation

1. Clone the repository or download the project files.
   ```sh
   git clone https://github.com/your-username/url-to-qr-code-generator.git
