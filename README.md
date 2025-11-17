# RikTok - Doomscroll your API failures 🚀

A lightweight, beautiful API client built with Tauri, Rust, and React. Experience the smoothest way to test your APIs with a stunning liquid glass UI.

![Version](https://img.shields.io/badge/version-0.1.0-blue)
![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)
![License](https://img.shields.io/badge/license-Proprietary-red)



https://github.com/user-attachments/assets/130d4274-070f-4554-91f1-48bbad611a2a



## ✨ Features

- 🎨 **Liquid Glass UI** - Beautiful, modern interface with glassmorphism design
- ⚡ **Lightning Fast** - Built with Rust and Tauri for native performance
- 📝 **Request History** - Automatically saves your recent requests (responses under 1MB)
- 🎯 **Multiple Request Types** - Support for GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS
- 🔐 **Authentication** - Bearer tokens, Basic auth, and API key support
- 📊 **Response Viewer** - Formatted JSON, syntax highlighting, and response metadata
- 🌙 **Dark Mode** - Easy on the eyes with a sleek dark interface
- 💾 **Persistent Storage** - Your requests and history are saved locally

## 📥 Download

### macOS

Download the latest version for your Mac:

- **Apple Silicon (M1/M2/M3)**: [RikTok_0.1.0_aarch64.dmg](https://github.com/aakashapoorv/riktok/releases/download/v0.1.0/RikTok_0.1.0_aarch64.dmg)

### System Requirements

- **macOS**: 10.15 (Catalina) or later
- **RAM**: 4GB minimum, 8GB recommended
- **Disk Space**: 100MB

## 🚀 Installation

### macOS

1. Download the appropriate `.dmg` file for your Mac
2. Open the downloaded `.dmg` file
3. Drag **RikTok** to your Applications folder
4. Open RikTok from Applications
5. If you see a security warning:
   - Go to **System Preferences** → **Security & Privacy**
   - Click **Open Anyway** to allow RikTok to run

**Note**: RikTok is not yet notarized by Apple, so you may need to allow it in Security & Privacy settings.

## 📖 Quick Start Guide

### Making Your First Request

1. **Enter a URL** in the request builder
2. **Select HTTP method** (GET, POST, etc.)
3. **Add headers** (optional) - Click the Headers tab
4. **Add request body** (optional) - Click the Body tab for POST/PUT requests
5. **Click Send** - View your response in the bottom panel

### Using Authentication

1. Click the **Auth** tab in the request builder
2. Choose your authentication type:
   - **None** - No authentication
   - **Bearer Token** - For JWT/OAuth tokens
   - **Basic Auth** - Username and password
   - **API Key** - Custom API key in header or query

### Viewing History

1. Click the **History** tab in the sidebar
2. Click any previous request to load it
3. Responses are saved if they're under 1MB
4. Export history as HTTP files or Postman collections

### Keyboard Shortcuts

- `Cmd + Enter` - Send request
- `Cmd + N` - New request
- `Cmd + ,` - Settings (coming soon)

## 🎨 Features Overview

### Request Builder
- Clean, intuitive interface
- Support for query parameters, headers, and body
- Multiple body types: JSON, Text, XML, Form Data, URL Encoded
- Real-time validation

### Response Viewer
- Formatted JSON with syntax highlighting
- Response headers and metadata
- Response time and size tracking
- Copy response to clipboard

### History
- Automatic request history tracking
- Saves responses under 1MB
- Search and filter (coming soon)
- Export capabilities

### Collections (Coming Soon)
- Organize requests into collections
- Share collections with your team
- Import/export Postman collections

## 🔒 Privacy & Data

- **All data is stored locally** on your machine
- **No telemetry or tracking** - Your requests are private
- **No internet connection required** except for making API calls
- Data is stored in: `~/Library/Application Support/com.riktok.app/`

## 🐛 Known Issues

- Collections feature is temporarily disabled (coming soon)
- Environment variables not yet implemented
- No Windows/Linux builds yet (macOS only for now)

## 💡 Tips & Tricks

1. **Quick Request Switching** - Use the History tab to quickly switch between recent requests
2. **Response Inspection** - Click on different tabs (Body, Headers, Metadata) to inspect all response details
3. **Copy Response** - Use the copy button to quickly copy response data
4. **Liquid Glass UI** - Enjoy the beautiful glassmorphism effects throughout the app

## 🔄 Updates

RikTok is under active development. Check back for updates and new features!

**Current Version**: 0.1.0  
**Release Date**: November 2025

## 📝 Changelog

### v0.1.0 (Initial Release)
- ✨ Beautiful liquid glass UI
- ⚡ Fast request execution with Rust backend
- 📝 Request history with response caching
- 🔐 Multiple authentication methods
- 📊 Formatted response viewer
- 💾 Local data persistence

## 🤝 Feedback & Support

Found a bug or have a feature request? We'd love to hear from you!

- **Issues**: [Report an issue](https://github.com/aakashapoorv/riktok/issues/new)

## 📜 License

RikTok is currently **proprietary software**. The source code will be open-sourced soon!

**© 2025 RikTok. All rights reserved.**

---

## ⚠️ Disclaimer

RikTok is provided "as is" without warranty of any kind. Use at your own risk. Always be careful when making API requests, especially to production environments.

---

**Made with ❤️ using Tauri, Rust, and React**

*Doomscroll your API failures in style* 😎
