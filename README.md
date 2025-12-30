# 🎵 Tezos Walkman - PWA NFT Audio Player

A badass retrowave-styled Progressive Web App for playing your Tezos audio NFTs from Objkt.com with full lock screen controls and background playback.

## ✨ Features

### 🎨 Retro Aesthetic
- Vaporwave gradient backgrounds
- Animated audio-reactive grid
- Circular frequency visualizer with 64 bars
- Neon glow effects that pulse with the music

### 📱 Full PWA Support
- **Install as App**: Add to home screen on iOS/Android
- **Offline Ready**: Works without internet (cached)
- **Lock Screen Controls**: Play/pause/next/prev on lock screen
- **Background Playback**: Keeps playing when you switch apps
- **Media Notifications**: Shows track info in notifications
- **Bluetooth Controls**: Works with car/headphone controls

### 🎧 Media Player Features
- Load Tezos audio NFTs from Objkt.com links
- Persistent playlist (saves to localStorage)
- Video NFT support (extracts audio for playback)
- Progress bar and track scrubbing
- Auto-play next track
- Clickable track titles link to Objkt

## 🚀 Installation

### Desktop
1. Open `walkman-player.html` in Chrome/Edge/Safari
2. Click the install icon in the address bar
3. Click "Install" to add to your desktop

### iOS (iPhone/iPad)
1. Open `walkman-player.html` in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add" in the top right

### Android
1. Open `walkman-player.html` in Chrome
2. Tap the menu (three dots)
3. Tap "Add to Home screen" or "Install app"
4. Tap "Install"

## 🎮 How to Use

1. **Add NFTs**: Paste an Objkt.com NFT link and click "ADD"
   - Format: `https://objkt.com/tokens/CONTRACT/TOKEN_ID`
   - Example: `https://objkt.com/tokens/KT1RJ6PbjHpwc3M5rw5s2Nbmefwbuwbdxton/129`

2. **Play Music**: Click the pink play button or tap any track in the playlist

3. **Lock Screen Controls**: 
   - Lock your phone/tablet
   - Controls appear on lock screen and in notifications
   - Play, pause, skip tracks without unlocking

4. **Background Play**: 
   - Switch to other apps - music keeps playing!
   - Perfect for browsing while listening

## 🔊 Lock Screen Features

When playing, you get:
- ✅ Track title, artist, and album art
- ✅ Play/Pause button
- ✅ Previous/Next track buttons
- ✅ Scrubber to seek through track
- ✅ 10-second skip forward/backward (on supported devices)
- ✅ Works with Bluetooth controls

## 🎨 Icons

All icons use retrowave vaporwave aesthetics:
- Gradient background (pink → purple → cyan)
- Dark walkman body with cassette window
- Pink glowing cassette reels
- Cyan play button with glow
- Gold LED indicator

Available sizes: 16×16 to 512×512 for all devices

## 🛠️ Technical Details

- **Framework**: Vanilla JavaScript (no dependencies!)
- **Audio**: Web Audio API for visualizer
- **PWA**: Service Worker + Manifest
- **Media**: Media Session API for lock screen
- **Storage**: LocalStorage for playlist persistence
- **NFT Data**: Objkt.com GraphQL API

## 📝 File Structure

```
walkman-player.html  - Main app file
manifest.json        - PWA manifest
sw.js               - Service worker
favicon.ico         - Browser favicon
icon-*.png          - App icons (all sizes)
apple-touch-icon.png - iOS home screen icon
```

## 🌐 Browser Support

- ✅ Chrome/Edge (Desktop & Mobile) - Full support
- ✅ Safari (iOS & macOS) - Full support
- ✅ Firefox (Desktop & Mobile) - Full support
- ⚠️ Samsung Internet - Partial (no Media Session)

## 💾 Offline Support

Once installed, the app works offline:
- ✅ Player UI loads without internet
- ✅ Previously loaded tracks in playlist
- ❌ Can't add new NFTs (requires API)
- ❌ Can't stream new tracks (requires IPFS)

## 🎯 Use Cases

- **Collectors**: Play your Tezos audio NFT collection
- **Artists**: Showcase your music NFTs
- **Curators**: Create playlists from Objkt
- **On-the-Go**: Mobile audio player for NFTs
- **Commute**: Background playback while traveling

## 🔥 Pro Tips

1. **Install as App** for best experience (no browser UI)
2. **Lock Screen** works best when installed as PWA
3. **Playlists Save** automatically - your collection persists
4. **Video NFTs** work too - audio is extracted
5. **Bluetooth** controls work when installed

## 🐛 Troubleshooting

**Lock screen controls not showing?**
- Make sure app is installed (not just bookmarked)
- Check that audio is actually playing
- Try restarting the app

**Can't play NFT?**
- Check the Objkt link is correct
- Verify it's an audio/video file (not image)
- Some IPFS gateways may be slow

**Playlist not saving?**
- Check browser allows localStorage
- Don't use private/incognito mode

## 🎨 Customization

Want to modify the style?
- All CSS is in `walkman-player.html`
- Vaporwave colors: `#ffd700` (gold), `#ff6ec7` (pink), `#00ffcc` (cyan)
- Edit `manifest.json` for app name/colors

## 📜 License

Free to use! Created for the Tezos NFT community.

---

**Built with 💜 for the Tezos ecosystem**

*Enjoy your NFT music collection in retrowave style!* 🌊🎵✨
