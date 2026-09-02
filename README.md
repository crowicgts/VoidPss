# VOID Private Server - redesigned website

## Files
- server.js - Express server + redesigned page
- public/logo.png - transparent VOID Private Server logo

## Run
1. Put `server.js` and the `public` folder together.
2. Install dependencies:
   npm install express cors
3. Use Node.js 18+.
4. Start:
   node server.js

The page keeps the GTPS Cloud live status endpoint from the original project.
The redesigned page adds:
- Growtopia-style pixel-world visuals
- VOID logo overlay
- animated red lightning
- pixel grass/world strip
- live server/player/port cards
- features section
- gallery
- responsive mobile layout
- Windows/Android/iOS/macOS setup modal
- music toggle
- EN/ID toggle
- improved navbar and footer

The two Growtopia screenshots are loaded from remote image URLs so you do not need to store extra image files. If you want fully local assets, replace those URLs in `server.js` with files in `public/assets`.
