# 📊 GST Calculator
**A high-precision, business-grade GST calculator built for mobile-first SaaS deployment.**

GST Calc is a dedicated financial tool for business owners, designed to handle professional accounting logic with 100% mathematical accuracy.

## ✨ Key Features
- **💎 Professional Reverse GST:** Extracts tax from total amounts (e.g., 2,00,000 - 5% = 1,90,476.19).
- **📝 Live Expression View:** Displays the full math equation (2 + 2 = 4) in real-time.
- **📱 PWA Ready:** Install it on your phone's home screen. Works offline.
- **🕒 Calculation History:** Automatically saves your last 30 entries locally.
- **🇮🇳 Indian Format:** Displays numbers in Lakhs and Crores (en-IN) with 2-decimal precision.

## 📱 Installation (PWA)
1. Open in your mobile browser.
2. **Android:** Tap the "Install App" banner at the top.
3. **iOS:** Tap the "Share" icon and select **"Add to Home Screen"**.

## 📐 Mathematical Audit
This app follows standard Indian accounting formulas:

| Type | Formula |
| :--- | :--- |
| **Forward GST (+)** | `Total = Base + (Base * Rate / 100)` |
| **Reverse GST (-)** | `Base = Total / (1 + (Rate / 100))` |

## 🛠️ Files in this Repo
- `index.html`: The core calculator app, UI, and logic.
- `manifest.json`: Configuration for the phone home-screen installation.
- `sw.js`: Service worker for offline capability.
- `my-app-icon.png`: The custom app branding.

---
*Built for precision. Used by business owners.*
