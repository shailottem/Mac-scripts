# Mac-scripts

This repository is for miscellaneous scripts I write for my Mac.

## `DownloadMonitoredFolderVideo.scpt`

This script automatically downloads videos from RSS feeds.

The videos are downloaded to `~/Downloads/Move to external drive` folder and sorted into subfolders by feed.

### Requirements

- [NetNewsWire](https://ranchero.com/netnewswire/) installed.
- In NetNewsWire, On My Mac account is turned on with a folder named "Monitored feeds".
- "Monitored Feeds" folder contains [YouTube RSS feeds](https://support.google.com/youtube/answer/6224202) to download.
- [youtube-dl](https://youtube-dl.org) installed.
- `webHelper.scpt` helper script is in `~/Library/Scripts Library`.
- Each video download will result in an open Terminal window; to close it after downloading, in `Terminal > Preferences > Profiles > Shell`, set "When the shell exists:" to close the window after shell exited, optionally only if the shell exited cleanly.

## `webHelper.scpt`

A helper script for web stuff.

Contains: 

- functions for downloading YouTube videos using [youtube-dl](https://youtube-dl.org).