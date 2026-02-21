This app is an Electron desktop tool that helps you install GOG/Steam manifest packs (ZIPs) by AppID, with a game-browser style UI.

What it does:

Lets you search Steam games by AppID or name.
Shows game details (description, screenshots, news, price, etc.).
Supports install queue, favorites, notes, and download history.
Downloads manifest ZIPs from multiple API sources (GitHub/PythonAnywhere) with source priority + fallback.
Verifies archive integrity and reports source/trust info.
Auto-installs extracted files into configured paths:
.lua files to your Lua base path, plus config and stplug-in
.manifest files to your manifest path (depot cache)
Has separate Settings for:
Lua install path
Manifest install path
Auto-detect Steam paths
Region/language/UI language
Speed limit, tray mode, AI options, etc.
Includes diagnostics to check source health/latency and show detected paths.
Has optional Discord Rich Presence and an AI helper chat (“Jeremy”).
In short: it’s a “find game -> fetch manifest pack -> place files in Steam-related folders” tool with UI conveniences and fallback/error handling around the download/install pipeline.
