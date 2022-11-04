# Goupil
 Firefox stylesheet

###### I named this repository "goupil" because it means "fox" 🦊 in old french 🇫🇷.

## How to install ?
### Firefox installed from the official installer
1. Open your currently active profile folder.
* Type or paste `about:support` in the address bar and press Enter to load it.
* Find the Profile Folder row and click "__Open Directory__" or "__Show in Finder__".
2. Make a new folder named `chrome` (all lower case).

### Firefox installed from the Miscroft Store
1. Type or paste `%LOCALAPPDATA%\Packages` into the File Manager address bar and press Enter to launch into the Packages folder.
2. Look for an entry starting with Mozilla.Firefox and click into that folder, then LocalCache, then Roaming, then Mozilla, then Firefox, then Profiles.

## Both cases
3. Install theme.
* Download "__userChrome.css__" and "__style__".
* Put these in your "__chrome__" folder.
4. Set Firefox look at userChrome.css at startup.
* In a new tab, type or paste "__about:config__" in the address bar and press Enter/Return. Click the button accepting the risk.
* In the search box type or paste "__userprof__", if you see `toolkit.legacyUserProfileCustomizations.stylesheets` then switch it to true.

# Features
Custom animated "About Firefox" window
Auto hide sidebar
Auto hide address bar buttons
Coloured lock icon in address bar
Auto hide disabled buttons (back, forward)
Animated bookmark bar

# Notes
You can mod this "theme" by removing lines of code in "__userChrome.css__" or by adding your own .css file in "__style__" and importing them in "__userChrome.css__".
