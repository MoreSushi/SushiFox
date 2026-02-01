# SushiFox

A personal Firefox setup with custom CSS, Sidebery layout, extensions, and UI tweaks.

![Preview of my Firefox](https://github.com/MoreSushi/SushiFox/blob/091450564a0d6a73503f964d9f55e5527c5eef45/Demo/demo.gif)

---

# Installation

### Requirements

* Firefox **147 ESR or newer**
* Firefox **Vertical Tabs OFF** (Sidebery replaces them)
* Download SushiFox files from **Releases** or source

---

### 1 — Enable Custom CSS Support

Open `about:config` and set:

```
toolkit.legacyUserProfileCustomizations.stylesheets → true
sidebar.revamp → false
widget.windows.mica.popups → 0
```

---

### 2 — Install Sidebery

Install:
[https://addons.mozilla.org/firefox/addon/sidebery/](https://addons.mozilla.org/firefox/addon/sidebery/)

---

### 3 — Copy Chrome Folder

* Open `about:profiles`
* Find **This is the profile in use**
* Click **Open Folder**
* Paste the SushiFox **chrome** folder inside
* Restart Firefox

---

### 4 — Import Sidebery Config

* Open Sidebery → **Settings**
* Scroll down to help → **Import settings**
* Import `sidebery.json`

Done — SushiFox should now be active.

---

# Extensions

## Recommended Extensions (Optional)

| Extension                                                                                        | Purpose                  |
| ------------------------------------------------------------------------------------------------ | ------------------------ |
| [**Sidebery**](https://addons.mozilla.org/firefox/addon/sidebery/)                               | Vertical tabs & tab tree |
| [**uBlock Origin**](https://addons.mozilla.org/firefox/addon/ublock-origin/)                     | Ad & tracker blocker     |
| [**Tampermonkey**](https://addons.mozilla.org/firefox/addon/tampermonkey/)                       | User scripts             |
| [Dark Reader](https://addons.mozilla.org/firefox/addon/darkreader/)                              | Global dark mode         |
| [Simple Translate](https://addons.mozilla.org/firefox/addon/simple-translate/)                   | Page translation         |
| [Holoschedule](https://addons.mozilla.org/firefox/addon/holo-schedule/)                          | Hololive schedule        |
| [Return YouTube Dislike](https://addons.mozilla.org/firefox/addon/return-youtube-dislikes/)      | Restore dislikes         |
| [SponsorBlock](https://addons.mozilla.org/firefox/addon/sponsorblock/)                           | Skip sponsor segments    |
| [YouTube Search Fixer](https://addons.mozilla.org/firefox/addon/youtube-suite-search-fixer/)     | Clean search results     |
| [YT Tweaks](https://addons.mozilla.org/firefox/addon/youtube-tweaks/)                            | YouTube UI tweaks        |
| [7TV](https://addons.mozilla.org/firefox/addon/7tv-extension/)                                   | Extra emotes             |
| [Gumbo](https://addons.mozilla.org/firefox/addon/gumbo-twitch-companion/)                        | Twitch tools             |
| [ani!search](https://addons.mozilla.org/firefox/addon/ani-search/)                               | Anime lookup             |
| [osu! preview](https://addons.mozilla.org/firefox/addon/osu-preview/)                            | Beatmap preview          |
| [osu! pp calculator](https://addons.mozilla.org/en-US/firefox/addon/pp-calculator/)              | PP calculator            |
| [Control Panel for Twitter](https://addons.mozilla.org/firefox/addon/control-panel-for-twitter/) | Remove Twitter/X clutter |

### Tampermonkey Scripts

| Script                                                                                           | Purpose              |
| ------------------------------------------------------------------------------------------------ | -------------------- |
| [Twitch Ad Blocker](https://github.com/pixeltris/TwitchAdSolutions/raw/master/vaft/vaft.user.js) | Block Twitch ads     |
| [osu! Background Grabber](https://greasyfork.org/fr/scripts/542558-osu-backgroundgrabber)        | Download backgrounds |
| [osu! Web Enhancement](https://greasyfork.org/fr/scripts/475417-osu-web-enhancement)             | osu! UI improvements |
| [osu! Plus](https://github.com/limjeck/osuplus/raw/master/osuplus.user.js)                       | Extra osu! features  |

### Suggested Pinned Extensions
- **Sidebery • uBlock Origin • Gumbo • Holoschedule • osu! pp calculator**

---

# Credits

* **[Firefox Downtown UI](https://github.com/oviung/DownToneUI-Firefox)** — Base theme with modified colors and details
* **[potatofox](https://codeberg.org/da157/potatofox)** — Icons and small code parts
* **[Win11 25H2 Monochrome Theme (Komorebi WM)](https://youtu.be/d1PvD31yQhc)** — Color palette inspiration
