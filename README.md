# IPTV4U Player

![IPTV4U Player Banner](https://raw.githubusercontent.com/mkshukeri/iptv4u-player/refs/heads/main/banner-github.png)

**IPTV4U Player** is a simple self-hosted IPTV player for your own M3U and M3U8 playlists.

It is built for users who want a clean, lightweight, and easy-to-use web player without installing Node.js, running a backend server, or setting up complicated dependencies.

Just open the player, load your playlist, choose a channel, and start watching.

---

## What IPTV4U Player Offers

Sometimes, all we need is a simple IPTV player that works directly from the browser.

No server setup.
No account.
No database.
No complicated installation.

IPTV4U Player is designed as a lightweight static web app that can be hosted anywhere, including GitHub Pages, Cloudflare Pages, Netlify, or any normal web hosting folder.

The goal is simple:

> Bring your own playlist, and IPTV4U Player will help you browse and play it beautifully.

Whether you want to watch your own playlist, test a playlist file, or host a simple player for personal use, IPTV4U Player keeps the experience straightforward.

---

## Key Features

* Self-hosted IPTV playlist player
* No Node.js required
* No backend server required
* No npm install required
* Built with plain HTML, CSS, and vanilla JavaScript
* Supports M3U and M3U8 playlist files
* Load playlist by URL
* Select local playlist file from your device
* Search channels easily
* Filter channels by group/category if available
* Display channel logo if available in the playlist
* Save last loaded playlist locally in browser storage
* Responsive design for desktop and mobile
* Dark blue glass-style interface
* Lightweight and easy to maintain

---

## How to Use

### Option 1: Load Playlist from URL

1. Open IPTV4U Player.
2. Select **Paste URL**.
3. Paste your M3U or M3U8 playlist URL.
4. Click **Load Playlist**.
5. Select a channel from the list.
6. Start watching.

Example playlist URL format:

```text
https://example.com/playlist.m3u
```

---

### Option 2: Load Playlist from Local File

1. Open IPTV4U Player.
2. Select **Select File**.
3. Choose your `.m3u` or `.m3u8` playlist file from your device.
4. Click **Open Playlist**.
5. Select a channel from the list.
6. Start watching.

This option is useful if you already have a playlist file saved on your computer or phone.

---

## How to Host It Yourself

IPTV4U Player is designed to run as a static web app.

You can host it using:

* GitHub Pages
* Cloudflare Pages
* Netlify
* Vercel static hosting
* Any normal web hosting
* Internal company web server
* Local browser file opening

Basic setup:

1. Download or clone this repository.
2. Upload the files to your static hosting.
3. Open `index.html` in your browser.
4. Load your own playlist.

No installation is required.

---

## Browser Support Note

IPTV4U Player uses the native HTML5 video player.

It does not include third-party streaming libraries such as `hls.js`.

Because of this, M3U8 or HLS playback depends on the browser and device support. Some browsers may play the stream directly, while others may not support the stream format natively.

For better HLS playback compatibility, try using Safari or a device/browser with native HLS support.

---

## Privacy

IPTV4U Player does not send your playlist to any backend server.

Your playlist is processed in your browser.

If you use the **Use Last Playlist** feature, the parsed playlist data is saved locally in your browser storage.

You can clear your browser storage anytime if you want to remove saved playlist data.

---

## Important Disclaimer

IPTV4U Player does not provide, host, sell, or distribute any IPTV content, playlist, TV channel, or streaming source.

This project is only a playlist player.

Users must use their own playlists or playlists that they are legally allowed to access.

---

## Who Is This For?

IPTV4U Player is useful for:

* Users who want a simple web-based IPTV player
* Users who prefer self-hosted tools
* Users who want to manage their own playlist
* Developers or users who want to test their IPTV playlist
* Anyone who wants a lightweight M3U/M3U8 player without backend setup

---

## Project Philosophy

IPTV4U Player is built around a simple idea:

> A useful tool does not always need to be complicated.

The player focuses on simplicity, ownership, and ease of use.

You bring your own playlist.
The app gives you a clean interface to browse and play it.

---

## Suggested Repository Topics

```text
iptv
iptv-player
m3u
m3u8
m3u-player
m3u8-player
html
css
javascript
vanilla-javascript
self-hosted
static-site
video-player
playlist-player
```

---

## License

Please use it responsibly and only with playlists or streams that you have the legal right to access.

