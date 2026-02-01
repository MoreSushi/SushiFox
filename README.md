# SushiFox
My own personal setup for Firefox (Includes Custom CSS with Sidebery, extensions, and config)
![Preview of my Firefox](https://i.imgur.com/EuqCIIU.gif)

## Prerequisites

- **Firefox v147** esr or later installed (untested on older versions)
- Vertical tabs if enabled must be DISABLED for Sidebery to work properly
- Downloaded the files from release section or from the source code directly 

## Instalation (with sidebery)

Type in the adress bar "about:config", press enter and change these settings :

-  **toolkit.legacyUserProfileCustomizations.stylesheets** : true
-  **sidebar.revamp** : false
-  **widget.windows.mica.popups** : 0

**Install [Sidebery](https://addons.mozilla.org/fr/firefox/addon/sidebery/)**

Go to **"about:profiles"** and look for the profiles in use. **Open your root profile folder** folder and place the chrome folder you downloaded in it.

**Close Firefox and reopen it** *(if you did all the steps sucessfully, the colours of the browser should have changed.)*

Go to **Sidebery settings** (right-click the Sidebery Icon -> Settings)

Scroll down all the way to the Help section and press **"Import settings"**
Select the **sidebery.json** file you downloaded.
