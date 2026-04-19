# Chat Stream Studio

## **Create AI Chat Animations Content for LinkedIn**
  
A free, open-source local web app by [CAIO Group](https://wearecaio.com) for creating animated GIF exports of AI chat streaming interactions — perfect for LinkedIn posts.

[![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![No install required](https://img.shields.io/badge/install-none-orange)](#how-to-use)
[![Works in browser](https://img.shields.io/badge/runs%20in-browser-blue)](#how-to-use)

---

## → [Download the app](chat-stream-studio.html)

Single HTML file. Open in any browser. No install, no server, no dependencies to install.

---

## What it does

Chat Stream Studio lets you animate a realistic AI chat conversation — complete with streaming text effects, thinking indicators, and custom branding — and export it as a GIF ready to post on LinkedIn.

## Requirements

| What | Required? |
|------|-----------|
| Modern browser (Chrome, Firefox, Safari, Edge) | ✅ Always |
| Internet connection | ✅ Only for GIF export + Google Fonts |
| Installation / Node / Python / server | ❌ Never |

> The live preview, all customization, and all settings work fully offline. An internet connection is only needed when you click **Export GIF** (to load the GIF encoder from a CDN) or when you search for a Google Font.

## Features

- **Five streaming styles** — Word fade + rise, Typewriter with caret, Char fade, Line reveal, and Blur in
- **Up to 4 chat bubbles** — Q1 → A1 → Q2 → A2, each AI response streams with its own thinking phase
- **Full visual customization** — colors, fonts (Google Fonts), cell shape, shadow, border widths, gradients
- **Avatar icons** — 16 built-in SVG icons + custom SVG upload for both user and AI
- **Custom header icon** — SVG icon picker + upload your own logo
- **Footer bar** — left / center / right branding text (great for company name, tagline, @handle)
- **LinkedIn-optimized formats** — Square 1080×1080, Portrait 4:5, Landscape 1200×628, Auto height
- **Google Fonts** — search and apply any of 37 curated fonts; carries into GIF export
- **8 one-click themes** — Default, Dark, Ocean, Warm, Mint, Purple, Slate, Brand Blue
- **Save / Load config** — export your settings as JSON and reload anytime
- **Play once or loop** — GIF plays once and stops by default; toggle looping in Export settings
- **Bubble tails** — toggle between rounded-pointer corner (classic chat bubble) and fully-rounded bubbles
- **Live preview controls** — play, pause, restart, scrub with progress bar

## How to use

1. **[Download `chat-stream-studio.html`](chat-stream-studio.html)**
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Customize your chat in the left panel
4. Click **Export GIF** → download your file
5. Post directly to LinkedIn

> **Tip:** Use **Auto height** format for long responses so nothing gets clipped.  
> Use **480×480 test** format first to check timing, then switch to 1080×1080 for the final export.

## Export tips for LinkedIn

| Format | FPS | Colors | Est. file size |
|--------|-----|--------|---------------|
| 1080×1080 square | 10 | 32 | ~1–2 MB |
| 1080×1350 portrait | 10 | 32 | ~1.5–3 MB |
| 1200×628 landscape | 10 | 32 | ~1–2 MB |

LinkedIn's GIF limit is **8 MB**. The app shows a warning above 5 MB and an error above 8 MB. Keep FPS ≤ 12 and palette colors ≤ 48 for large formats.

## License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE).

---

Made with ♥ by Stefanos Karagos · [CAIO Group](https://wearecaio.com)
