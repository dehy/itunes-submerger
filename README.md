# iTunes SubMerger
http://itunes.flyingpingu.com.com

## Overview

**iTunes SubMerger** is a collection of AppleScripts that automatically download and merge subtitles into your favorite TV shows in iTunes. **It's easy and really fast**. It's perfect for Series Lovers with an iPad or an aTV.

## Prerequisites

* TV show files should be in .m4v or .mp4 format.
* Metadatas have to be correctly filled ("Show", "Season Number" and "Episode Number" in the "Video" tab of track informations)

## Howto

1. Copy "Betaseries Grab Subtitles for selected tracks.scptd" and "Remove subtitles of selected tracks.scptd" to ~/Library/iTunes/Scripts/ (create Scripts/ if not present)
2. Open iTunes and select a TV Show in your iTunes Library
3. Click the script menu (between Window and Help menu in status bar) and select "Betaseries Grab Subtitles for selected tracks"
4. Select the language for the subtitles
4. Enjoy!

## Removing subtitles

1. Select the TV Shows episodes you want to purge
2. Click the script menu and select "Remove subtitles of selected tracks"

## Known bugs & limitations

* You can actually only merge one subtitle at a time: French or Enligh. You choose.
* The downloaded subtitle is the last subtitle registred in betaseries.com. It's not always the best.
* When adding a subtitle to an episode currently playing,  paused or just stopped, you need to open another media file and then reopen your episode in order to iTunes to "see" the subtitle.
* If the show name is not exactly the same as in betaseries.com, the script crash.
* There is no progress indicator.

## Credits

iTunes SubMerger uses SublerCLI from the [Subler project](http://code.google.com/p/subler/)  
Huge thanks to [betaseries.com](http://www.betaseries.com)