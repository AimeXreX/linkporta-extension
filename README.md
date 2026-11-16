<div align="center">

<img src="assets/icon.png" width="96" alt="LinkPorta">

# LinkPorta — Send to Telegram

**One click from any video, post or song to your Telegram.**

[فارسی](README.fa.md) · [Download](../../releases/latest) · [Website](https://linkporta.prosysteam.ir/extension) · [Telegram bot](https://t.me/LinkPorta_Bot) · [Privacy](PRIVACY.md)

</div>

LinkPorta adds a **“Send to Telegram”** button to YouTube, Instagram, TikTok, X, SoundCloud, Spotify, Pinterest, Reddit, Facebook, Aparat, Vimeo, Twitch and Threads, and with “all websites” mode on, to 1,000+ other video and audio sites. Click it and the [@LinkPorta_Bot](https://t.me/LinkPorta_Bot) Telegram bot delivers the file to your chat, with a live progress bar.

## Features
- **Floating button** on video/post pages (collapses after a few seconds, never in the way)
- **Hover button** on every downloadable link: feeds, search results, comments
- **Right-click** any link or page on *any* website → “Send to Telegram”
- **Popup:** send the current page, see recent sends and their status, settings
- **Optional “all websites” mode:** the button on 1,000+ more video and audio sites; asks for permission only when you turn it on
- Telegram login (no password), dark/light theme, Persian RTL interface
- Works on Chrome, Edge, Brave, Opera and any Chromium browser

## Install
1. Download `linkporta-extension-<version>.zip` from the [latest release](../../releases/latest) and extract it.
2. Open `chrome://extensions` (Edge: `edge://extensions`) and turn on **Developer mode**.
3. Click **Load unpacked** and select the extracted `linkporta-extension` folder.
4. Click the LinkPorta icon → **Log in with Telegram**.

Optional: check the download with the `.sha256` file from the same release:
```bash
sha256sum -c linkporta-extension-<version>.zip.sha256
```

> A Chrome Web Store version is on the way; it will update automatically.

## Privacy first
Link detection runs **entirely inside your browser**. No browsing history, page content or visited URLs ever leave your device. Only when *you* click the button is that single link sent to LinkPorta. Details in [PRIVACY.md](PRIVACY.md).

### Permissions
| Permission | Why |
|---|---|
| `storage` | your login key and settings, stored locally |
| `contextMenus` | the right-click “Send to Telegram” item |
| `activeTab`, `scripting` | show the button on the page you are viewing |
| `linkporta.prosysteam.ir` | send the link you clicked to the LinkPorta bot |
| `<all_urls>` *(optional)* | only if you turn on “all websites” in the popup |

## Support & security
Questions or problems: [@LinkPortaSup_Bot](https://t.me/LinkPortaSup_Bot). Found a security issue? See [SECURITY.md](SECURITY.md).

---
© ProSyS. All rights reserved. This repository contains the release builds and documentation only.
Font: [Vazirmatn](https://github.com/rastikerdar/vazirmatn) by Saber Rastikerdar (SIL OFL 1.1).
