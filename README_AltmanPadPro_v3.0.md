# 🌐 AltmanPad Pro v3.0 – Global Creator Tool

**Create. Reflect. Share. Empower.**  
AltmanPad Pro™ is a fully-featured Progressive Web App (PWA) designed to empower global creators with tools for visual expression, storytelling, and connected action.

---

## ✨ Features

- 🎨 **Hand-drawing Canvas** with undo/redo, color, size, brush type
- 🎥 **Timelapse Recording** (Frame capture + export-ready structure)
- 🧠 **Gemini AI Summarization** of ZINE text (Google API)
- 💸 **QRU Gratitude System** with Zapier Webhook support
- 📘 **Notion Integration** (Page creation via API)
- 🌍 **SNS Posting** via custom Webhooks (e.g., Zapier → Instagram/X)
- 📱 **Responsive PWA UI**, ready for mobile/tablet/desktop
- 🔐 API key entry via UI (Gemini, Notion, Zapier, SNS)

---

## 📦 Tech Stack

- **Next.js + React**
- **Tailwind CSS**
- **next-pwa** for service worker & offline support
- **fetch API** for integration with external tools

---

## 🚀 Deployment (Vercel Recommended)

1. Clone or download this repository
2. Set up environment keys via the UI:
   - Gemini API Key
   - Notion Integration Key + Page ID
   - Zapier Webhook URL
   - SNS Webhook URL
3. Deploy via [Vercel](https://vercel.com/import) from GitHub

---

## 🔧 Developer Notes

- Canvas state is auto-recorded per action
- MP4 export will be supported via `ffmpeg.js` in upcoming version
- QRU actions are customizable via Zapier / automation platforms

---

## 📘 License & Credits

© 2025 PaxPits Universe  
AltmanPad™ is a project by [Pax4671](https://github.com/Pax4671) for global empathy, co-creation, and shared futures.

---

> “It all begins with the light you drew.”  
> — AltmanPad Philosophy
