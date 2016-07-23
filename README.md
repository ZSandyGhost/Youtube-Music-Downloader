# Youtube-Music-Downloader

Download music from your favourite Youtube channels!

# Requirements:
- youtube-dl: ```sudo apt install youtube-dl```
- ffmpeg: ```sudo apt install ffmpeg```
- BeautifulSoup: ```sudo pip3 install BeautifulSoup4```

# Usage: 
  Add your Youtube channels to 'ytm-channels.conf' file
```bash
usage: ytm [-h] [-n [NUMBER]] [-a] [-u USER]

Youtube music downloader

optional arguments:
  -h, --help            show this help message and exit
  -n [NUMBER], --number [NUMBER]
                        Number of music per channel [1-30]
  -a, --auto            Automatically download new music that are not already
                        downloaded
  -u USER, --user USER  Download music from a specified user
```

# Command Line Example:
    $ python3 ytm -a
    $ python3 ytm -a -n 10
    $ python3 ytm -u AllTrapNation -n 10
