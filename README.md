# Insta Bot

## Description
This project is an Instagram bot built using Python. It automates interactions such as following users and managing followers. The bot leverages Instagram's web interface and automates actions using Selenium.

## Features
- Log in to Instagram automatically.
- Search for a specific user and follow them if not already following.
- Follow multiple users from a given list or criteria.
- Manage modal dialogs during automation.

## Technologies Used
- Python
- Selenium for browser automation
- ChromeDriver for controlling the Chrome browser
- WebDriverWait and expected conditions for robust interaction handling

## Prerequisites
- Python 3.x installed
- Chrome browser installed
- ChromeDriver matching your Chrome version

## Code Overview
### Login
The `login` method automates the login process by:
- Navigating to Instagram's login page.
- Locating the username and password fields.
- Submitting the credentials and verifying login success.

### Find User
The `find_user` method:
- Navigates to the specified user profile.
- Attempts to follow the user if not already followed.
- Opens the user's followers list for further actions.

### Follow Users
The `follow` method:
- Locates and clicks on "Follow" buttons for a specified number of users.
- Handles modal dialogs that may interfere with the process.

### Close
The `close` method terminates the browser session by quitting the WebDriver.

## Usage
1. Update the code with your Instagram credentials.
2. Run the script using:
   ```bash
   python insta_bot.py
   ```
3. Use methods like `login`, `find_user(account_name)`, and `follow(number)` to perform actions.

## Disclaimer
Use this bot responsibly. Automating interactions on Instagram may violate its terms of service. Ensure compliance with platform policies to avoid potential bans.

## Author
**Shaikh Sameer**
-[GitHub Profile](https://github.com/Sameershaikh001)
