# Settings to Change on New Computer:

### General Settings
* Show battery percentage
* Change startup programs
    * Lastpass
* Play sound effects through Internal Speakers.  Sound > Play sound effects through
* Show date and day of week in menu bar. Date & Time > Clock > Show Date, Show the day of the week

### Keyboard/Mouse
* Move trackpad tracking speed to fastest setting
* Enable one finger tap to click
* Click > Light
* Use Seil to switch caps lock key with escape
    * Change the caps lock key > Change the caps lock key > keycode > 53
    * Other Keys > Change Escape > keycode > 57
* [Enable 3 finger drag](https://support.apple.com/en-us/HT204609)

### File Syncing
* Onedrive
    * Add Temp folder to favorites sidebar
* Dropbox

### Iterm
* Sync settings with Dropbox
    * Preferences > Load Preferences From a custom folder or URL > Point to Dropbox folder
* Activate theme
    1. iTerm2 > Preferences > Profiles > Colors Tab
    2. Open the Color Presets... drop-down in the bottom right corner
    3. Select Import... from the list
    4. Select the itermcolors file
    5. Select the theme from Color Presets...
* [Enable Session Restoration](https://www.iterm2.com/documentation-restoration.html)

### Vim
* Install Plugins via Vundle by running :PluginInstall

### Alfred
* Register Powerpack License
* Disable Spotlight, replace with Alfred 3
    * Remove Spotlight shortcut by opening Keyboard > Shortcuts > Spotlight > Show Spotlight Search
    * Change Alfred hotkey to command + space
* Exclude folders from Spotlight search
    * go, golang, Github, CS 6310- TA folders
* Set up Settings Syncing
    * Advanced > Syncing > Set Sync Folder

### BetterTouchTool
* Load license and import settings from Odrive/Encrypted folder

### Rescuetime
* Launch and login

### Calendar:
* Add Google Account
* Uncheck Google Calendars: Contacts, Visits, Birthdays (Other)
* Preferences -> Alerts -> Birthdays (Set to None)

### Chrome
* Make default browser, sign in to load history, extensions, etc
#### Vimium
* Excluded URLs and keys

**Patterns**|**Keys**
:-----:|:-----:
|`http*://mail.google.com/*`|giojkr/p|
|`http*://inbox.google.com/*`|giojkr/p|
|`https://www.reddit.com/*`|aszxhjk|

* Custom Key Mappings
```
map w removeTab
map W restoreTab
unmap x
unmap X
map I LinkHints.activateModeToOpenIncognito
map O moveTabToNewWindow
map z visitPreviousTab
map <c-]> passNextKey
map <c-f> LinkHints.activateModeWithQueue
map <c-m> toggleMuteTab
```

* Custom Search Engines
```
# Wikipedia
w: http://en.wikipedia.org/wiki/Special:Search?search=%s
# Stack Overflow
so: http://stackoverflow.com/search?q=%s
# YouTube
y: http://www.youtube.com/results?search_query=%s
```
* Remove f in Characters used for link hints

#### Google Dictionary
* Uncheck "Display pop-up when I double-click a word"
* Check " Display pop-up when I select a word or phrase".  Make sure trigger key is Command.
* Change trigger key when Display pop-up when I double-click a word
