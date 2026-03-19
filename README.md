# 📱 WhatsApp Android for iOS (PWA)

A Progressive Web App (PWA) that brings the **Android WhatsApp interface** to iPhone. It uses a custom "wrapper" to host the real WhatsApp Web service while removing Safari's browser bars.

---

## 🚀 Quick Setup (iPhone Safari)

1. **Open the Site:** Click your [GitHub Pages Link](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/) in **Safari**.
2. **Add to Home Screen:** Tap the **Share** button (Square with up arrow) and select **"Add to Home Screen"**.
3. **Launch:** Open the new WhatsApp icon from your home screen.
4. **Login:** - Take a photo of the QR code using another device.
   - On your main WhatsApp phone, go to **Settings > Linked Devices**.
   - Scan the photo of the QR code.

---

## ✨ Features
- **Android Material UI:** Custom green header with Android-style icons.
- **Standalone Mode:** No Safari URL bar or bottom navigation buttons.
- **iPhone Notch Support:** Uses `viewport-fit=cover` to blend with the Dynamic Island.
- **Persistent Sessions:** Stays logged in like a real app.

## 🛠 Project Structure
- `index.html`: The main "engine" and UI layout.
- `manifest.json`: Configuration for the PWA standalone mode.
- `icon.png`: The icon used for the Home Screen.
- `.gitignore`: Keeps the repository clean of system junk.

---

> **Note:** This is a web-based shortcut (PWA) and is not affiliated with Meta/WhatsApp. It simply provides a custom view of the official WhatsApp Web.
