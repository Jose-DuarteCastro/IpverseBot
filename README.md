# 🌐 IpverseBot - Your Telegram Companion for IP Range Insights 🤖

![IpverseBot](https://img.shields.io/badge/IpverseBot-telegram-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)

Welcome to the **IpverseBot** repository! This Telegram bot provides essential information about IP ranges, featuring multi-language support and a user-friendly interface. With capabilities to fetch ASN data from ipinfo.io, it delivers detailed reports for any country. 

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Admin Panel](#admin-panel)
- [Coin System](#coin-system)
- [Referral Program](#referral-program)
- [Caching](#caching)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Multi-language Support**: Users can interact with the bot in their preferred language.
- **ASN Data Retrieval**: Fetches Autonomous System Number (ASN) data from ipinfo.io.
- **Comprehensive Reports**: Generates detailed IP range reports for any country.
- **Admin Panel**: Manage bot settings and user interactions easily.
- **Coin System**: Users can earn coins through interactions, enhancing engagement.
- **Referral Program**: Invite friends and earn rewards.
- **Smart Caching**: Improves performance by caching frequently requested data.

## Technologies Used

- **Python**: The core language for bot development.
- **Telegram Bot API**: For creating the bot and handling user interactions.
- **Docker**: To containerize the application for easy deployment.
- **ipinfo.io API**: For fetching IP-related data.
- **SQLite**: For local data storage.
- **Flask**: To serve the admin panel.

## Installation

To get started with IpverseBot, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Jose-DuarteCastro/IpverseBot.git
   cd IpverseBot
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your Telegram Bot API key and other necessary configurations.

4. **Run the Bot**:
   You can run the bot using:
   ```bash
   python bot.py
   ```

5. **Docker Deployment** (Optional):
   If you prefer using Docker, build and run the container:
   ```bash
   docker build -t ipversebot .
   docker run -d ipversebot
   ```

## Usage

Once the bot is running, you can interact with it through Telegram. Simply search for the bot by its username and start chatting. The bot will guide you through its features and commands.

## Commands

Here are some of the main commands you can use:

- `/start`: Start the bot and see the welcome message.
- `/help`: Get a list of available commands.
- `/ipinfo [IP]`: Fetch information about a specific IP address.
- `/country [Country Name]`: Get IP range reports for a specific country.
- `/coins`: Check your current coin balance.
- `/refer [username]`: Invite a friend to earn referral coins.

## Admin Panel

The admin panel allows you to manage the bot easily. You can access it through a web interface. To set it up, ensure you have Flask installed and run the admin server:

```bash
python admin.py
```

You can then navigate to `http://localhost:5000` in your web browser.

## Coin System

The coin system adds a layer of interaction. Users can earn coins by using commands and referring friends. You can check your balance and redeem coins for special features.

## Referral Program

Invite your friends to use the bot and earn rewards. Each successful referral will increase your coin balance, giving you access to premium features.

## Caching

To improve performance, IpverseBot uses smart caching. Frequently requested data is stored temporarily, reducing the load on the API and speeding up response times.

## Contributing

We welcome contributions! If you have ideas or suggestions, feel free to fork the repository and submit a pull request. Please ensure your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest releases, visit the [Releases](https://github.com/Jose-DuarteCastro/IpverseBot/releases) section. Download the latest version and execute it to enjoy all the features of IpverseBot. 

If you have any questions or need support, check the [Releases](https://github.com/Jose-DuarteCastro/IpverseBot/releases) section for updates and information. 

Thank you for your interest in IpverseBot! Enjoy exploring the world of IP ranges with ease.