# 🔖 Multi-Column Bookmarks for Chrome

<div align="center">

![Version](https://img.shields.io/badge/version-1.3-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Chrome](https://img.shields.io/badge/chrome-extension-orange.svg)
![Manifest](https://img.shields.io/badge/manifest-v3-yellow.svg)

**Browse your bookmarks in a beautiful multi-column grid layout**

[Features](#-features) • [Installation](#-installation) • [Screenshots](#-screenshots) • [Configuration](#-configuration) • [Contributing](#-contributing)

---

</div>

## 🎯 The Problem

Chrome's native bookmark manager shows bookmarks in a **single narrow column**, forcing you to:
- ❌ Scroll endlessly through hundreds of bookmarks
- ❌ Waste valuable screen space
- ❌ Squint at tiny sidebar text
- ❌ Click multiple times to find what you need

## ✨ The Solution

**Multi-Column Bookmarks** transforms your bookmark browsing experience with:
- ✅ **2-5 column grid layout** - see 5x more bookmarks at once
- ✅ **Lightning-fast search** - find any bookmark instantly
- ✅ **Keyboard shortcuts** - access bookmarks without touching your mouse
- ✅ **Fully customizable** - themes, sizes, behaviors all configurable
- ✅ **Zero learning curve** - works just like native bookmarks, but better

---

## 🚀 Features

### 📊 Multi-Column View
Browse bookmarks in a responsive grid (2-5 columns) instead of a single list. Perfect for users with hundreds or thousands of bookmarks.

### 🔍 Instant Search
Type to filter bookmarks in real-time. Search by title or URL across all your bookmarks and folders.

### ⌨️ Keyboard Shortcuts
- **`Ctrl+Shift+B`** - Open extension popup
- **`Ctrl+Shift+F`** - Open and focus search box
- Fully customizable via Chrome shortcuts

### 🎨 Customizable Appearance
- **Themes**: Light, Dark, or Auto (follows system)
- **Adjustable popup size**: 600-1200px width, 400-800px height
- **Font sizes**: 10-14px for perfect readability
- **Compact mode**: Maximize bookmarks per screen
- **Custom accent colors**: Make it yours

### 🎯 Smart Behaviors
- **Open in**: New Tab, Background Tab, Current Tab, or New Window
- **Auto-close**: Close popup after opening bookmark
- **Remember location**: Pick up where you left off
- **Search on type**: No need to press Enter

### 📁 Folder Navigation
- Click folders to browse contents
- Breadcrumb navigation to go back
- Visual folder indicators
- Shows bookmark count per folder

### 🌐 Website Favicons
Beautiful site icons for easy visual identification (can be toggled off)

### 💾 Cloud Sync
All settings automatically sync across your Chrome devices

---

## 📸 Screenshots

### Main Interface
```
┌─────────────────────────────────────────────────────────┐
│  Search bookmarks...           Columns: [3] ⟳ ⚙️       │
├─────────────────────────────────────────────────────────┤
│  🏠 Home › Work Projects › Client Sites                 │
├─────────────────────────────────────────────────────────┤
│                                                           │
│  📁 Documentation    📁 Design Assets    📁 Staging      │
│  🔖 Project Alpha    🔖 Dashboard UI     🔖 Analytics    │
│  🔖 Client Portal    🔖 Style Guide      🔖 Reports      │
│  🔖 Admin Panel      🔖 Component Lib    🔖 API Docs     │
│  📁 Archives         🔖 User Testing     🔖 Changelog    │
│                                                           │
│  ... and 45 more bookmarks                               │
├─────────────────────────────────────────────────────────┤
│                    127 bookmarks                          │
└─────────────────────────────────────────────────────────┘
```

---

## 📥 Installation

### From Release (Recommended)

1. **Download** the latest release: [multi-column-bookmarks-v1.3.zip](../../releases)
2. **Extract** the zip file to a folder
3. **Open Chrome** and navigate to `chrome://extensions/`
4. **Enable** "Developer mode" (toggle in top-right)
5. **Click** "Load unpacked" button
6. **Select** the extracted folder
7. **Done!** The extension icon appears in your toolbar

### From Source

```bash
git clone https://github.com/yourusername/multi-column-bookmarks.git
cd multi-column-bookmarks
```

Then follow steps 3-6 above, selecting the cloned folder.

---

## ⚙️ Configuration

### Quick Start

1. Click the extension icon to open
2. Click the ⚙️ button for settings
3. Customize your experience
4. Close and reopen popup to see changes

### Keyboard Shortcuts Setup

1. Go to `chrome://extensions/shortcuts`
2. Find "Multi-Column Bookmarks"
3. Click the pencil icon
4. Set your preferred shortcuts

### Recommended Settings

**For Power Users:**
```
Columns: 5
Compact Mode: ON
Font Size: 11px
Open Behavior: New Tab (Background)
Shortcut: Ctrl+B
```

**For Simplicity:**
```
Columns: 3
Font Size: 13px
Theme: Auto
Close on Open: ON
Shortcut: Ctrl+Shift+B
```

---

## 📚 Documentation

- [Installation Guide](INSTALL.md) - Detailed installation instructions
- [Settings Guide](SETTINGS_GUIDE.md) - Complete settings reference
- [Development Guide](DEVELOPMENT.md) - For developers and contributors

---

## 🛠️ Tech Stack

- **Manifest V3** - Latest Chrome extension standard
- **Vanilla JavaScript** - No frameworks, lightning fast
- **Chrome Bookmarks API** - Native bookmark access
- **Chrome Storage API** - Settings sync across devices
- **CSS Grid** - Responsive multi-column layouts

---

## 🎯 Use Cases

### For Developers
- Quick access to documentation sites
- Organized project bookmarks
- API reference collections
- Stack Overflow favorites

### For Researchers
- Academic paper collections
- Reference material libraries
- Research topic folders
- Citation management

### For Marketers
- Campaign tracking links
- Competitor analysis sites
- Tool collections
- Resource libraries

### For Students
- Course material organization
- Study resource collections
- Assignment links
- Academic portals

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Report Bugs
Open an issue with:
- Clear description
- Steps to reproduce
- Expected vs actual behavior
- Chrome version
- Extension version

### Suggest Features
Open an issue with:
- Feature description
- Use case / motivation
- Mockups or examples (if applicable)

### Submit Pull Requests
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 Changelog

### Version 1.3 (Current)
- ✨ Added comprehensive settings page
- ✨ Keyboard shortcuts support
- ✨ Dark mode theme
- ✨ Custom accent colors
- ✨ Configurable open behaviors
- 🐛 Fixed bookmark loading errors
- 🐛 Improved error handling
- 📚 Added extensive documentation

### Version 1.2
- 🐛 Fixed service worker registration
- 🐛 Fixed TypeError in bookmark navigation
- 📚 Added development guide

### Version 1.1
- 🎨 Compact layout improvements
- 📊 Added bookmark counter
- 🐛 Bug fixes and stability improvements

### Version 1.0
- 🎉 Initial release
- 📊 Multi-column grid layout
- 🔍 Real-time search
- 📁 Folder navigation
- 🌐 Favicon support

---

## 💡 Tips & Tricks

### Maximize Efficiency
1. Use keyboard shortcuts for instant access
2. Enable "Close on Open" for quick bookmark launches
3. Set "New Tab (Background)" to queue multiple sites
4. Use Compact Mode to see more bookmarks

### Organize Better
1. Use folders to group related bookmarks
2. Name bookmarks descriptively for better search
3. Remove unused bookmarks regularly
4. Use breadcrumbs to navigate quickly

---

## 📄 License

MIT License

Copyright (c) 2026 Multi-Column Bookmarks

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 📞 Support

- **Issues**: [GitHub Issues](../../issues)
- **Discussions**: [GitHub Discussions](../../discussions)

---

## 🌟 Star History

If you find this extension useful, please consider giving it a star! ⭐

---

<div align="center">

**Made with ❤️ for bookmark enthusiasts**

[⬆ Back to Top](#-multi-column-bookmarks-for-chrome)

</div>
