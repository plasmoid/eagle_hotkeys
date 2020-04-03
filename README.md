# Hotkeys for EAGLE 9

Hotkeys have been copied from this post by an unknown author
https://www.element14.com/community/message/34527/l/useful-keyboard-shortcuts#34527

This repo adapts these to Eagle V9.

There are 2 versions of the hotkeys, one for Windows with `CTRL` and one for macOS with `CMD` key. (Both versions should work on both OSes)

If you want to use only part of the hotkeys you should look at 'by type' folder. Name of the file describes the editor which uses it.

`eaglerc.default` is a backup of a standard `eaglerc` (9.2.2).

## Installation

### macOS
1. Close Eagle! (eaglerc gets overwritten on close, so don't edit it while Eagle is open)
2. Open `~/Library/Application\ Support/Eagle/settings/<version/` -> pick your latest version
3. Backup your current `eaglerc` file
4. Paste desired hotkeys from the `macOS` folder in this repo at the end of your `eaglerc` file
5. Open Eagle.

### Windows
Download file `eaglerc` in the Windows folder and copy it into `c:\users\[USERNAME]\AppData\Roaming\Eagle\settings\<version>\`.

If you want to use only part of these, just copy lines that you need into your `eaglerc` file.

## Known Issues
These hotkeys reference a lot of custom ULP scripts that are missing. Feel free to make some of them and submit a pull request.
