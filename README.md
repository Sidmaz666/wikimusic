# wikimusic
A CLI Tool to Play Classical Music. The script scrapes from <a href="https://en.wikipedia.org/wiki/Wikipedia:List_of_sound_files/Baa%E2%80%93Bac">Free Wikipedia Sound Library</a>.

# Dependencies

1. curl
2. mpv

# Installation

       sudo cp wikimusic /usr/bin

# Showcase

<img src="https://github.com/Sidmaz666/wikimusic/blob/main/assets/preview.gif" width="100%">

# Usage

	wikimusic [USAGE]: [OPTIONS]
	
	wikimusic -r - Play Random Songs Until You Stop
	wikimusic -H - Show History
	wikimusic -h, wikimusic --help - Show Help

	Example:

	wikimusic
	
	Note: The Application Provides an interactiva Menu!

	[MISC]
	
	Cache Directory : $HOME/.cache/wikimusic
	TMP_DIRECTORY : /tmp/wikimusic
