# goupil
a Firefox stylesheet

###### „goupil“ is an old-fashioned way to say „fox“ in French.

## features
- stolen (I forgot from whom =[) animated "About Firefox" window
- automatically hiding sidebar
- automatically hiding address bar buttons
- coloured address bar security icon
- automatically hiding disabled navigation (back and forward) buttons
- animated bookmark bar

## installation

### on a regular Firefox installation
1. open the profile directory of the profile on which is theme should be installed.
* type or paste `about:support` in the address bar and press Enter to load it.
* find the `Profile Folder` row and click, depending of the system, either `Open Directory` or `Show in Finder`.
2. make a new folder named `chrome`.

### on a Microsoft Store Firefox installation
1. input `%LOCALAPPDATA%\Packages` into the File Manager address bar and press Enter.
2. look for an entry starting with `Mozilla.Firefox` and click into that folder, then LocalCache, then Roaming, then Mozilla, then Firefox, then Profiles.

### on any Firefox installation
3. install theme.
* download `userChrome.css` and `style`.
* put both in the `chrome` directory.
4. make Firefox check `userChrome.css` at startup.
* input `about:config` in the Firefox address bar and press Enter.
* in the search bar, input `userprof`; if `toolkit.legacyUserProfileCustomizations.stylesheets` can be seen, toggle it on.
