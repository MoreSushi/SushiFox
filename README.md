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

