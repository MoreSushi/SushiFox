# SushiFox

A personal Firefox setup that includes custom CSS styling, Sidebery layout, extensions, and configuration tweaks.

![Preview of my Firefox](https://github.com/MoreSushi/SushiFox/blob/091450564a0d6a73503f964d9f55e5527c5eef45/Demo/demo.gif)

---

## What You Need Before Starting

Make sure you have:

- Firefox **version 147 ESR or newer** installed (older versions may not work correctly)
- **Vertical tabs turned OFF** in Firefox settings (Sidebery replaces them)
- The SushiFox files downloaded from the **Releases** section or the source code

---

## Installation Guide (Using Sidebery)

Follow these steps carefully. No technical experience is required.

---

### Step 1 — Enable Firefox Custom Styling

1. Click the address bar in Firefox.
2. Type: `about:config`  
3. Press Enter.
4. Accept the warning if it appears.

Search for each setting below and change the value as shown:

- `toolkit.legacyUserProfileCustomizations.stylesheets` → set to **true**
- `sidebar.revamp` → set to **false**
- `widget.windows.mica.popups` → set to **0**

To change a value, click the toggle button on the right side of the setting.

---

### Step 2 — Install Sidebery

Install the Sidebery extension from the Firefox Add-ons store:

Sidebery: https://addons.mozilla.org/firefox/addon/sidebery/

---

### Step 3 — Copy the Chrome Folder

1. In the Firefox address bar, type: `about:profiles`
2. Press Enter.
3. Find the profile labeled **“This is the profile in use”**
4. Click **Open Folder** next to it.
5. In the folder that opens, paste the **chrome** folder you downloaded from SushiFox.

---

### Step 4 — Restart Firefox

Close Firefox completely, then open it again.

If everything worked, the browser’s appearance should now look different.

---

### Step 5 — Import Sidebery Settings

1. Click the Sidebery icon in your toolbar.
2. Right-click the icon and choose **Settings**.
3. Scroll to the bottom of the page.
4. In the Help section, click **Import settings**.
5. Select the included `sidebery.json` file.

---

## Done

Your SushiFox setup should now be fully active.

### Optional — Recommended Extensions

> These extensions are **optional** and not required for SushiFox to work.

| Extension                                                                                        | What it does                              |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------- |
| [Sidebery](https://addons.mozilla.org/firefox/addon/sidebery/)                                   | Advanced vertical tabs & tab tree manager |
| [uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/)                         | Lightweight ad & tracker blocker          |
| [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/)                           | Runs custom user scripts                  |
| [Dark Reader](https://addons.mozilla.org/firefox/addon/darkreader/)                              | Dark mode for all websites                |
| [Simple Translate](https://addons.mozilla.org/firefox/addon/simple-translate/)                   | Quick page & text translation             |
| [Holoschedule](https://addons.mozilla.org/firefox/addon/holo-schedule/)                          | Hololive stream schedule viewer           |
| [Return YouTube Dislike](https://addons.mozilla.org/firefox/addon/return-youtube-dislikes/)      | Restores dislike counts                   |
| [SponsorBlock](https://addons.mozilla.org/firefox/addon/sponsorblock/)                           | Skips sponsored video segments            |
| [YouTube Search Fixer](https://addons.mozilla.org/firefox/addon/youtube-suite-search-fixer/)     | Cleans YouTube search results             |
| [YT Tweaks](https://addons.mozilla.org/firefox/addon/youtube-tweaks/)                            | Extra YouTube UI controls                 |
| [7TV](https://addons.mozilla.org/firefox/addon/7tv-extension/)                                   | Adds Twitch/YouTube emotes                |
| [Gumbo — Twitch Companion](https://addons.mozilla.org/firefox/addon/gumbo-twitch-companion/)     | Twitch chat & stream tools                |
| [ani!search](https://addons.mozilla.org/firefox/addon/ani-search/)                               | Anime recognition from images             |
| [osu! preview](https://addons.mozilla.org/firefox/addon/osu-preview/)                            | Beatmap preview in browser                |
| [osu! pp calculator](https://addons.mozilla.org/en-US/firefox/addon/pp-calculator/)              | Performance point calculator              |
| [Control Panel for Twitter](https://addons.mozilla.org/firefox/addon/control-panel-for-twitter/) | Removes Twitter/X clutter & ads           |

---

#### Tampermonkey User Scripts

| Script                                                                                           | What it does               |
| ------------------------------------------------------------------------------------------------ | -------------------------- |
| [Twitch Ad Blocker](https://github.com/pixeltris/TwitchAdSolutions/raw/master/vaft/vaft.user.js) | Blocks Twitch ads          |
| [osu! Background Grabber](https://greasyfork.org/fr/scripts/542558-osu-backgroundgrabber)        | Downloads osu! backgrounds |
| [osu! Web Enhancement](https://greasyfork.org/fr/scripts/475417-osu-web-enhancement)             | Improves osu! website UI   |
| [osu! Plus](https://github.com/limjeck/osuplus/raw/master/osuplus.user.js)                       | Extra osu! site features   |

---

#### 📌 Suggested Pinned Extensions

Sidebery • uBlock Origin • Gumbo • Holoschedule • osu! pp calculator
