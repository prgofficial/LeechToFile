# Telegram Torrent Leecher 🔥🤖

### A Telegram Torrent (and youtube-dl) Leecher based on [Pyrogram](https://github.com/pyrogram/pyrogram)

## This is a leech to FILE repo! Leech to STREAM(video) availabe here > [LEECH TO STREAM](https://github.com/prgofficial/LeechToStream)


### For Support join here [MoviezOnlySupport](https://telegram.dog/moviezonlysupport)
### Working example group [Leech Here](https://telegram.dog/leechtorrentmoviesonly)


# Benefits :-
    ✓ Telegram Torrent/Directlink leecher with its unzipping, unrar and untar
    ✓ Custom file name, thumbnail
    ✓ Custom commands
	✓ Added /clearall command to clear the downloads which are not deleted automatically.
	✓ Added support for youtube playlist ( use /pytdl )


### Credit goes to SpEcHiDe for his [Publicleech](https://github.com/SpEcHiDe/PublicLeech) repo

### Thank [Gautam Kumar](https://github.com/gautamajay52/TorrentLeech-Gdrive) for the added Cool features 🤩

## Installing

### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/prgofficial/LeechToFile)


### The Legacy Way

Simply clone the repository and run the main file:

```sh
git clone https://github.com/prgofficial/LeechToFile
cd LeechToFile
virtualenv -p /usr/bin/python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
# <Create config.py appropriately>
python3 -m tobrot
```

### an example config.py 👇
```py
from tobrot.sample_config import Config

class Config(Config):
  TG_BOT_TOKEN = ""
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  AUTH_CHANNEL = -1001234567890
```


## Available Commands

* `/ytdl`: This command should be used as reply to a [supported link](https://ytdl-org.github.io/youtube-dl/supportedsites.html)

* `/leech`: This command should be used as reply to a magnetic link, a torrent link, or a direct link. [this command will SPAM the chat and send the downloads a seperate files, if there is more than one file, in the specified torrent]

* `/leech archive`: This command should be used as reply to a magnetic link, a torrent link, or a direct link. [This command will create a .tar.gz file of the output directory, and send the files in the chat, splited into PARTS of 1024MiB each, due to Telegram limitations]

* `/leech unzip`: This will unzip the .zip file and dupload to telegram.

* `/leech unrar`: This will unrar the .rar file and dupload to telegram.

* `/leech untar`: This will untar the .tar file and upload to telegram.




## Credits, and Thanks to
* [Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [Robots](https://telegram.dog/Robots) for their [@UploadBot](https://telegram.dog/UploadBot)
* [@AjeeshNair](https://telegram.dog/AjeeshNait) for his [torrent.ajee.sh](https://torrent.ajee.sh)
* [@gotstc](https://telegram.dog/gotstc), @aryanvikash, [@HasibulKabir](https://telegram.dog/HasibulKabir) for their TORRENT groups
* [![CopyLeft](https://telegra.ph/file/b514ed14d994557a724cb.jpg)](https://telegra.ph/file/fab1017e21c42a5c1e613.mp4 "CopyLeft Credit Video")
