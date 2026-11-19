# IPTVnator Umbrel Community App Store 📺

Official community app package for **IPTVnator** on **umbrelOS**.

![IPTVnator Banner](https://raw.githubusercontent.com/4gray/iptvnator/master/apps/tv/docs/screenshots/home.webp)

## Features

- 🌐 **Self-hosted IPTVnator Web App & Backend** running 24/7 on your Umbrel server.
- 📺 **Companion Backend for LG webOS & Samsung Tizen Smart TVs**: provides CORS proxying, stream parsing, and metadata synchronization.
- 📱 **Phone Setup with QR Code**: scan the QR code on your TV to add playlists, Xtream Codes, or Stalker portal details from your mobile browser.
- 🚀 **Optimized for Massive Catalogs**: pre-configured with 512MB response buffers and increased Node.js memory limits for high-volume IPTV providers.
- 🔒 **Persistent Storage**: playlists, server sources, and state are preserved across reboots on Umbrel storage.

---

## 🚀 How to Install on Umbrel

1. Open your **Umbrel** web dashboard (`http://umbrel.local` or your Umbrel IP).
2. Go to the **App Store**.
3. Open the **App Store settings** (three dots in the top right corner) and select **Community App Stores**.
4. Paste the repository URL:
   ```text
   https://github.com/deFIATer/iptvnator-umbrel
   ```
5. Click **Add**.
6. Find **IPTVnator** in the App Store and click **Install**!

---

## 📺 Connecting your LG webOS Smart TV

1. On your LG Smart TV, open **IPTVnator TV**.
2. Go to **Settings → Connection** (or the welcome setup screen).
3. In **IPTVnator backend URL**, enter your Umbrel server address:
   ```text
   http://<YOUR_UMBREL_IP>:4333/api
   ```
4. Click **Check and connect**.
5. In **Settings → Library & sync → Server library**, select **Use this server's sources**.

---

## 🛠️ Credits & Upstream

- Upstream Project: [4gray/iptvnator](https://github.com/4gray/iptvnator)
- Packaged for Umbrel by: [deFIATer](https://github.com/deFIATer)
- Template: [getumbrel/umbrel-community-app-store](https://github.com/getumbrel/umbrel-community-app-store)
