# 🇧🇩 iptv-bangladesh

[![IPTV](https://img.shields.io/badge/type-iptv%20playlist-blue)](https://github.com/tunnabri-ops/iptv-bangladesh)
[![Language](https://img.shields.io/badge/UI-Bangla%20%2B%20English-orange)](https://github.com/tunnabri-ops/iptv-bangladesh)

**Free-to-air Bangladeshi TV channels in one playlist — open it in VLC or any IPTV player, or play a single channel right in your browser.**

> বাংলা সংস্করণ নিচে আছে। / Bangla version below.

## ✨ Features

- **11 Bangladeshi channels** in `playlist_bangladesh.m3u8` — ATN Bangla, Bangla Vision, Boishakhi TV, DBC News, Ekushey TV, Gazi TV, Maasranga TV, NTV, RTV, Ekhon TV and Duronto TV
- **4 streams live-confirmed** (checked 2026-11-23): Bangla Vision, Boishakhi TV, Ekushey TV, NTV
- **Single-channel browser player** — `index.html` plays one channel's `.m3u8` link with HLS support

## 🚀 How to use

| Way | Steps |
|---|---|
| 📺 VLC / IPTV player | Download `playlist_bangladesh.m3u8` and open it in VLC or any IPTV player |
| 🌐 Browser | Open `index.html`, paste a single channel's `.m3u8` link, press **Play** |

## ⚠️ Honest limits

- Only **free-to-air** channels. No paid or unofficial paid streams.
- 7 of the 11 streams could not be verified from this VM (connection failed) — **not proven dead**, they may still play in Bangladesh.
- T Sports was removed — its stream URL returns HTTP 404 (checked 2026-11-23).
- The playlist file is a **channel list, not a video** — it will not auto-play on the web page. Play one channel at a time.

## 🇧🇩 বাংলা

**IPTV বাংলাদেশ — ফ্রি-টু-এয়ার বাংলাদেশি চ্যানেলের প্লেলিস্ট।**

- `playlist_bangladesh.m3u8` ডাউনলোড করে VLC / IPTV Player-এ খুলুন, অথবা
- `index.html` খুলে একটা চ্যানেলের `.m3u8` লিংক বসিয়ে Play চাপুন
- শুধু ফ্রি চ্যানেল — কোনো পেইড স্ট্রিম নয়

## 📄 License

MIT — use it however you like; credit is appreciated.
