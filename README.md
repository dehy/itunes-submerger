# iTunes SubMerger

## Overview

TV Show subtitles, now in your iTunes, iPad, iPhone and iPod touch. 2 clicks, 5 seconds. Enjoy.

You can sync your iPad or any other iDevice. Then you will be able to select the subtitle in the player.

## Prerequisites

* TV show files should be in .m4v or .mp4 format.
* Metadatas have to be filled ("Show", "Season Number" and "Episode Number" in the "Video" tab of track informations)

## Howto

1. Copy "Betaseries Grab Subtitles for selected tracks" and "Remove subtitles of selected tracks" to ~/Library/iTunes/Scripts/ (create Scripts/ if not present)
2. Open iTunes and select a TV Show in your iTunes Library
3. Click the script menu (between Window and Help menu in status bar) and select "Betaseries Grab Subtitles for selected tracks"
4. Select the language for the subtitles
4. Enjoy!

## Reseting subtitles

1. Select the TV Shows episodes you want to purge
2. Click the script menu and select "Remove subtitles of selected tracks"

## Known bugs & limitations

* You can actually only merge one subtitle, French or Enligh.
* The downloaded subtitle is the last subtitle registred in betaseries.com. It's not always the best.
* When adding a subtitle to an episode playing, paused or even stopped, you need to open another media file and then reopen your episode in order to iTunes to "see" the subtitle.
* If the show name is not exactly the same as in betaseries.com, the script crash.
* There is no progress indicator.

## Credits

Huge thanks to Maxime Valette for its work on Betaseries.com