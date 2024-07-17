# BIT-Chatter-Bot Documentation

## Overview

The BIT-Chatter-Bot is a chatbot specifically designed for Bannari Amman Institute of Technology. It is built using PHP and provides an interactive interface for users to chat and get responses.

## Project Structure

- **chatbot/**
  - **bot.php**: The main PHP script that handles the chatbot logic and responses.
  - **message.php**: Handles incoming messages and interacts with `bot.php` to fetch responses.
  - **style.css**: Contains the CSS styles for the chatbot interface.
  - **README.md**: Project documentation providing setup instructions and usage details.

## Features

- Interactive chat interface for users.
- PHP-based backend to handle message processing and responses.
- Simple and intuitive design with easy-to-use interface.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/SabarishCodeWizard/bit-chatter-bot.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd bit-chatter-bot/chatbot
   ```
3. **Setup a Local Server:**
   - Ensure you have a local server setup (e.g., XAMPP, WAMP, MAMP).
   - Place the `chatbot` directory in the `htdocs` directory (or equivalent) of your local server.

4. **Start the Local Server:**
   - Start your local server (Apache).

5. **Access the Chatbot:**
   - Open your web browser and navigate to `http://localhost/chatbot`.

## Usage

1. **Open the Chatbot Interface:**
   - Navigate to `http://localhost/chatbot` in your web browser.
2. **Start Chatting:**
   - Enter your message in the input field and press Enter.
   - The chatbot will respond based on the predefined logic in `bot.php`.

## Contributing

1. **Fork the Repository:**
   ```bash
   git fork https://github.com/SabarishCodeWizard/bit-chatter-bot.git
   ```
2. **Create a New Branch:**
   ```bash
   git checkout -b feature/your-feature
   ```
3. **Make Your Changes and Commit:**
   ```bash
   git commit -am 'Add new feature'
   ```
4. **Push to the Branch:**
   ```bash
   git push origin feature/your-feature
   ```
5. **Create a New Pull Request:**
   - Go to the repository on GitHub and create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
