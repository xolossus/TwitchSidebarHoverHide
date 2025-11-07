# 🎨 Twitch Sidebar Hover Hide

A small HTML/CSS/JS modification for Twitch that hides the left sidebar automatically until your mouse is hovering over it.  
Perfect for users who like a **simplified Twitch interface with no distractions**, yet still want easy access to followed channels.

---

## 🖥️ Overview

The **Twitch Sidebar Hover Hide** script modifies Twitch’s interface to automatically conceal the sidebar.  

When you move your cursor to the left edge of the screen, the sidebar smoothly slides into view.  
Move your mouse away — it hides again. It’s simple, elegant, and immersive.

---

## ⚙️ Features

- 🧹 **Clean Layout** – Removes clutter by hiding the sidebar when it’s not in use.  
- 🖱️ **Hover to Reveal** – Sidebar appears instantly when you hover near the left edge.  
- ⚡ **Lightweight Implementation** – Pure HTML/CSS/JS — no extensions or dependencies required.  
- 🎮 **Non-intrusive** – Does not interfere with Twitch’s core functionality or player behavior.  

---

## 🧭 Installation

You can use it in the following ways:

### 🔹 Option 1: As a Browser Script

1. Install [Stylus](https://add0n.com/stylus.html).  
2. Copy the **CSS portion from `TwitchSidebarHoverHide.html`.  
3. Paste it into a new custom style set to run on "URLs starting with": `https://www.twitch.tv`.

### 💻 Option 2: As a Local HTML File

1. Download or clone this repository.  
2. Open `TwitchSidebarHoverHide.html` in your browser.  
3. Follow the instructions or copy the embedded CSS into your Twitch customization setup.  

---

## 🧠 How It Works

The script adds a small CSS rule and a few event handlers that:

- Adjust the Twitch sidebar’s width to `0` or hide it via `transform: translateX(-100%)`.  
- Detect mouse hover near the left screen edge to reveal the sidebar with a smooth transition.  
- Use minimal JavaScript for optional hover detection.  

---

## 📜 License

[MIT License](LICENSE)

## 👤 Author

xolossus

Designed for a seamless quality viewing experience.
