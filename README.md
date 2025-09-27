# 🚀 X-DM-Followers: Automate Your Direct Messages on X (formerly Twitter)

![X-DM-Followers](https://img.shields.io/badge/version-1.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-yellow.svg)

Welcome to the **X-DM-Followers** repository! This Python script allows you to send direct messages to all users who follow your X account. With options for headless browsing and detailed debugging logs, this tool simplifies your messaging needs.

## 📥 Download the Latest Release

To get started, download the latest version of the script from the [Releases](https://github.com/Gideon-K-Addai/X-DM-Followers/releases) section. Once downloaded, execute the script to begin sending DMs to your followers.

## 📖 Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Headless Browser Option](#headless-browser-option)
6. [Debugging Logs](#debugging-logs)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## 🌟 Features

- **Automated Messaging**: Send direct messages to all your followers with ease.
- **Headless Browser Support**: Run the script without opening a browser window.
- **Detailed Debugging Logs**: Keep track of all actions taken by the script.
- **User-Friendly Interface**: Simple command-line interface for easy navigation.

## ⚙️ Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.8 or higher
- Pip (Python package installer)

### Step-by-Step Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Gideon-K-Addai/X-DM-Followers.git
   ```

2. **Navigate to the Directory**:

   ```bash
   cd X-DM-Followers
   ```

3. **Install Required Packages**:

   Use pip to install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

## 🛠️ Usage

After installation, you can run the script from the command line. Use the following command:

```bash
python x_dm_followers.py
```

Follow the prompts to log in to your X account and send messages to your followers.

## 🔧 Configuration

Before running the script, you need to configure your settings. Open the `config.json` file and fill in your X account details:

```json
{
  "username": "your_username",
  "password": "your_password",
  "message": "Your custom message here"
}
```

## 🖥️ Headless Browser Option

To run the script in headless mode, simply add the `--headless` flag when executing the script:

```bash
python x_dm_followers.py --headless
```

This option allows the script to run in the background without opening a browser window, making it perfect for automated tasks.

## 📜 Debugging Logs

The script generates detailed logs of all actions taken. These logs can help you troubleshoot any issues that arise. You can find the logs in the `logs` directory. 

### Log Levels

- **INFO**: General information about the script's operation.
- **DEBUG**: Detailed information useful for debugging.
- **ERROR**: Information about any errors encountered.

## 🤝 Contributing

We welcome contributions! If you want to help improve X-DM-Followers, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [Gideon-K-Addai](https://github.com/Gideon-K-Addai)
- **Email**: your_email@example.com

## 🌐 Topics

This repository covers a variety of topics, including:

- Direct Messaging
- Headless Browsing
- Selenium WebDriver
- Python Programming

Explore the full list of topics below:

- direct-message
- dm
- dm-tool
- headless
- headless-browser
- messager
- messaging
- python
- selenium
- selenium-webdriver
- twitter
- twitter-dm
- twitter-dm-tool
- twitter-dmer
- twitter-dmer-tool
- x
- x-dm
- x-dmer
- x-dmer-tool
- x-twitter

## 📊 Example Workflow

1. **Set Up**: Install the required packages and configure your settings.
2. **Run the Script**: Execute the script to send messages.
3. **Check Logs**: Review the logs for any errors or issues.
4. **Adjust Configuration**: Modify the message or settings as needed.

## 🎉 Conclusion

X-DM-Followers provides a simple yet powerful way to engage with your followers on X. Whether you are a marketer, influencer, or just looking to connect with your audience, this tool is designed to help you achieve your goals efficiently.

For the latest version, visit the [Releases](https://github.com/Gideon-K-Addai/X-DM-Followers/releases) section and download the script. Happy messaging!