# iTunes SubMerger

## Overview

TV Show subtitles, now in your iTunes, iPad, iPhone and iPod touch. 2 clicks, 5 seconds. Enjoy.

## Prerequisites

I assume your TV Shows are in mp4 or m4v file format (non-jailbroken iDevices compatible file formats)

## Howto

1. Copy "Betaseries Grab Subtitles for selected tracks" and "Remove subtitles of selected tracks" to ~/Library/iTunes/Scripts/ (create Scripts/ if not present)
2. Open iTunes and select a TV Show in your iTunes Library
3. Click the script menu (between Window and Help menu in status bar) and select "Betaseries Grab Subtitles for selected tracks"
4. Select the language for the subtitles
4. Enjoy!

## Reseting subtitles

1. Select the TV Shows episodes you want to purge
2. Click the script menu and select "Remove subtitles of selected tracks"

## Known bugs

* When removing subtitles, if the episode has no subtitles, the script exists with an error
* The last subtitle referenced on Betaseries.com is automatically selected as "best subtitle" available. It is purely arbitrary (even true for 720p releases)