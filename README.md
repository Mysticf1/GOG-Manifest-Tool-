A lightning-fast, lightweight desktop application built with Rust and Tauri designed to streamline installing GOG and Steam manifest packs (ZIPs) by AppID, featuring a sleek game-browser style interface.

### ✨ What It Does
* **Game Discovery:** Search Steam games effortlessly by AppID or name.
* **Rich Metadata:** View game details, descriptions, screenshots, news, and pricing.
* **Queue & Organization:** Manage install queues, save favorites, take notes, and track your download history.
* **Smart Downloads:** Fetch manifest ZIPs from multiple API sources (GitHub/PythonAnywhere) featuring automatic source priority and fallback handling.
* **Integrity & Trust:** Verify archive integrity and check source trust metrics before installing.
* **Automated Installation:** Seamlessly extract and place files into your configured directories:
  * `.lua` files straight to your Lua base path, config, and `stplug-in`
  * `.manifest` files right into your manifest depot cache path
* **Advanced Settings:** Fully configurable paths for Lua and manifests, auto-detect Steam path functionality, language preferences, speed limits, tray mode, and AI options.
* **Diagnostics:** Built-in health checks for source latency and detected directory validation.
* **Extras:** Optional Discord Rich Presence integration and an AI helper chat ("Jeremy").

In short: It’s your all-in-one, high-performance "find game -> fetch manifest pack -> auto-deploy files" pipeline, backed by Rust speed and Tauri efficiency. 🦀⚡

New version V4 is in rust - tauri. Older version before V4 are in electron, all apis have been moved client sided to server side and have been rotated from previous leaks
