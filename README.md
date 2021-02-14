# tordown

This is a rewrite of Bugswriter's pirokit script.  It removes some of the icons
and defaults to use rofi.  There are a few other changes I updated the search
to allow multiple keyword searches.

NOTE: I use transmission so I have also changed this and used a default user and
password see the comments in the scripts to change the user and password if you
are not using the defaults.  (And if you are they should be changed.)

### Bugswriter originally READEME.md
This script is used to web scrape a very popular torrent site 1337x.to to search
torrents using bash, and you can represent scrapped torrent data in fzf / dmenu
/ rofi sort of like menu to select which torrent to download.

## Installation

Place this script where you keep your scripts.

```bash
chmod +x tordown
```

## Usage
```
tordown "search query"
```
or if you use without search query it's by default going to ask take input with
rofi.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to
discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
