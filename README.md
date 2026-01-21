# 🛠️ AusCan Diagnostics
**Professional Australian CAN Bus Diagnostics & Fixes**

[![PWA Status](https://img.shields.io/badge/PWA-Installable-brightgreen)](https://auscan.com.au)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)](https://github.com/yourusername/auscan-pwa/graphs/commit-activity)

AusCan Diagnostics is a lightweight, mobile-first **Progressive Web App (PWA)** designed for Australian automotive enthusiasts and professional workshops. We bridge the gap between complex fault codes and affordable repairs by providing direct links to rectified OEM and OEM+ parts.

---

## 🚀 Features
- **Offline First**: Works in workshop "dead zones" using advanced service worker caching.
- **Cost Squashing**: Direct links to vetted suppliers (AliExpress, eBay AU, RockAuto) for common AU vehicle faults.
- **Mobile Optimized**: Built specifically for deployment and use from devices like the Google Pixel 8.
- **Golden Records**: Verified diagnostic data for the Ford Ranger (PX series), Holden Commodore (Alloytec/SIDI), and BMW X5 (N57).

---

## 📱 Getting Started (Mobile-Only Setup)

This project is designed to be managed entirely from a mobile device using **Spck Editor**.

### Prerequisites
1. Install [Spck Editor](https://play.google.com/store/apps/details?id=io.spck) from the Play Store.
2. A [GitHub](https://github.com) account.
3. A [Vercel](https://vercel.com) account for instant deployment.

### Installation & Deployment
1. **Clone the Repo**: Open Spck Editor, tap the Git icon, and clone this repository.
2. **Local Preview**: Tap the green "Play" button in Spck to preview the PWA.
3. **Push Changes**:
   - Tap the Git icon -> **Commit** (add a message like "Update manifest").
   - Tap **Push** to send changes to GitHub.
4. **Auto-Deploy**: Link your GitHub repo to Vercel. Every push from your phone will automatically update the live site.

---

## 📁 Project Structure
```text
├── index.html          # Core PWA landing page & UI
├── manifest.json       # PWA metadata for "Add to Home Screen"
├── sw.js               # Service Worker for offline caching
├── pwa-192x192.png     # Standard App Icon
└── pwa-512x512.png     # Maskable Android Icon
