
YouTube Enhancer – Custom Browser Extension
===========================================

A lightweight browser extension that customizes your YouTube experience with:

- ✅ Playback speed controls
- ✅ Distraction-free mode (hides sidebar, comments, end screens)
- ✅ Shorts blocker (removes YouTube Shorts)
- ✅ Custom keyboard shortcuts
- ✅ Dark YouTube-style popup UI
- ✅ Persistent settings using browser.storage.local

Features
--------

| Feature                 | Description |
|------------------------|-------------|
| 🔊 Speed Control         | Speed up, slow down, or reset playback rate from popup or with shortcut keys |
| 🧹 Distraction-Free Mode | Hides sidebar, comments, info panels, and end screens |
| ❌ Shorts Blocker        | Removes Shorts sections from homepage, sidebar, and channel tabs |
| ⌨️ Custom Shortcuts       | Set your own Shift+key bindings for speed control and toggles |
| 💾 Persistent Settings   | All preferences are saved across sessions |

Installation (Temporary for Development)
----------------------------------------

**Firefox**

1. Open `about:debugging#/runtime/this-firefox` in Firefox
2. Click “Load Temporary Add-on…”
3. Select the `manifest.json` file from the extracted folder
4. Visit https://www.youtube.com and click the extension icon to access features

⚠️ Firefox removes temporary extensions after a browser restart. You'll need to reload it when you reopen the browser.

Usage
-----

- Open any YouTube video
- Click the extension icon
- Use the buttons to:
  - Adjust speed
  - Toggle distraction-free mode
  - Block/restore Shorts
- Use the Settings panel to customize keyboard shortcuts
- Your choices are saved automatically

Default Shortcut Keys (Shift + key)

| Action                   | Key |
|--------------------------|-----|
| Toggle Distraction-Free  | D   |
| Speed Up                 | +   |
| Speed Down               | -   |
| Reset Speed              | 0   |

You can change these in the settings panel.

Project Structure
-----------------

youtube-enhancer/
├── manifest.json
├── background.js
├── popup.html
├── popup.js
├── content.js
├── icon16.png   ← optional
├── icon48.png   ← optional
├── icon128.png  ← optional

License
-------

This project is free to use and modify. No attribution required, but appreciated. Built for fun, learning, and better video-watching.
