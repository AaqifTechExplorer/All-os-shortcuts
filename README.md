# ⌨️ All OS Shortcuts Reference

### 🪟 Windows • 🍎 macOS • 🐧 Linux

> **A fast, interactive, bilingual keyboard-shortcut reference for desktop operating systems.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 🌟 Overview

**All OS Shortcuts Reference** is a single-page web application that brings keyboard shortcuts for **Windows, macOS, and Linux** together in one clean interface.

Instead of searching the web every time you forget a shortcut, simply open the reference, search for what you need, and copy the shortcut.

The interface supports **বাংলা and English**, making the reference useful for both Bengali and English-speaking users.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🪟 **Windows** | Windows 10 & Windows 11 shortcut references |
| 🍎 **macOS** | Finder, Mission Control, screenshots, text editing & more |
| 🐧 **Linux** | Desktop-environment-specific shortcuts |
| 🌐 **Bilingual UI** | বাংলা + English |
| 🔎 **Instant Search** | Search shortcuts by key or task |
| ⌨️ **Live Detection** | Detect supported keyboard combinations |
| 📋 **One-Click Copy** | Click a shortcut to copy it |
| 📱 **Responsive** | Works across desktop, tablet & mobile |
| ♿ **Accessibility** | Keyboard focus, reduced motion & contrast support |
| 🎯 **Priority Categories** | Most-used shortcuts are shown first |

---

## 🖥️ Supported Platforms

### 🪟 Windows

Includes shortcuts for:

- ⭐ Most Used
- 🪟 Window Snapping & Management
- 🖥️ Virtual Desktops & Task View
- 📁 File Explorer
- 🔍 Taskbar, Widgets & Search
- ✍️ Text Editing
- ⚙️ System & Accessibility

Windows shortcuts can also vary between **Windows 10 and Windows 11**.

### 🍎 macOS

Includes:

- ⭐ Most Used
- 🪟 Windows & Mission Control
- 📁 Finder
- 📸 Screenshots & Media
- ✍️ Text Editing
- ⚙️ System & Accessibility

### 🐧 Linux

Linux shortcuts are organized around desktop environments rather than treating every Linux installation as identical.

Supported environments include:

- GNOME
- KDE Plasma
- Cinnamon
- XFCE

---

## 🔎 Powerful Search

Search for either a **shortcut** or the **task it performs**.

For example:

```text
Ctrl C
copy
screenshot
File Explorer
terminal
```

The matching shortcut cards are automatically filtered and highlighted.

You can also use:

```text
Ctrl + K
```

or:

```text
Cmd + K
```

to quickly focus the search box.

Press:

```text
Esc
```

to clear the search.

---

## ⌨️ Live Keyboard Detection

The application can listen for keyboard combinations that browsers are allowed to receive.

When a matching shortcut is detected, its card is highlighted.

However, some shortcuts are handled directly by the operating system before the browser receives the key event.

Those shortcuts are marked accordingly instead of pretending they can be detected by the website.

> 🔒 **OS-controlled shortcuts cannot always be detected by a normal web page.**

---

## 📋 Copy Any Shortcut

Every shortcut card can be clicked to copy its key combination.

For example:

```text
Ctrl + Shift + Esc
```

Click the card → shortcut copied to your clipboard.

---

## 🌐 বাংলা + English

The interface includes two languages:

**বাংলা**

> Windows, macOS ও Linux শর্টকাট গাইড

**English**

> Windows, macOS, and Linux Shortcuts Guide

Switch between them instantly from the language selector.

---

## 📱 Responsive Design

The interface adapts to different screen sizes:

```text
Desktop
   ↓
Tablet
   ↓
Mobile
```

On smaller screens, the navigation sidebar becomes a mobile menu to preserve screen space.

---

## 🎨 UI Highlights

The interface uses:

- Dark theme
- Keyboard-style `<kbd>` elements
- Shortcut cards
- Category navigation
- Search highlighting
- Responsive grids
- Animated shortcut matching
- OS and version selectors
- Fixed status bar

The project is intentionally designed to feel closer to a **desktop keyboard-reference tool** than a traditional documentation page.

---

## 🛠️ Built With

This project uses standard web technologies:

```text
HTML5
CSS3
Vanilla JavaScript
```

No framework is required.

No Node.js installation is required.

No build system is required.

No backend is required.

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/all-os-shortcuts-reference.git
```

Then:

```bash
cd all-os-shortcuts-reference
```

### Run locally

The simplest option is to open:

```text
all_os_shortcuts.html
```

directly in your browser.

Or start a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/all_os_shortcuts.html
```

---

## 📂 Project Structure

```text
all-os-shortcuts-reference/
│
├── all_os_shortcuts.html
├── README.md
└── LICENSE
```

The current application is intentionally self-contained in a single HTML file.

---

## 🧩 Customization

The shortcut datasets are stored directly inside the JavaScript section of the HTML file.

This makes it easy to:

- Add new shortcuts
- Remove shortcuts
- Change descriptions
- Add categories
- Add OS variants
- Improve translations
- Modify the interface

---

## 🤝 Contributing

Contributions are welcome.

You can contribute by:

- Adding missing shortcuts
- Correcting inaccurate shortcuts
- Improving translations
- Adding desktop-environment support
- Improving accessibility
- Fixing responsive issues
- Improving browser compatibility
- Improving the UI

### Contribution workflow

```bash
git checkout -b feature/new-shortcuts
```

Make your changes, then:

```bash
git add .
git commit -m "Add new keyboard shortcuts"
git push origin feature/new-shortcuts
```

Open a Pull Request on GitHub.

---

## ⚠️ Accuracy & Compatibility

Shortcut behavior can vary depending on:

- Operating-system version
- Desktop environment
- Keyboard layout
- Application
- Manufacturer customizations
- User-defined keybindings

This is especially important on Linux, where desktop environments can define different default shortcuts.

The project should therefore be treated as a **practical reference**, not an absolute specification for every computer.

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to:

- ✅ Use
- ✅ Copy
- ✅ Modify
- ✅ Distribute
- ✅ Publish
- ✅ Use commercially

See the [LICENSE](LICENSE) file for the complete license text.

---

## ⭐ Support the Project

If this project is useful to you:

**⭐ Star the repository**

It helps the project become easier for others to discover.

---

## 👨‍💻 Author

**AaqifTechExplorer**

Built as a practical, cross-platform keyboard-shortcut reference.

---

<div align="center">

### ⌨️ Learn the shortcuts. Work faster.

**Windows • macOS • Linux**

</div>
