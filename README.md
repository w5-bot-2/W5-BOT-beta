



# ð±W5-BOTð¤ (Beta)




## `Scan QR`

[`Click Here For get Session String`](https://replit.com/@WH173-5P1D3R/W5-BOT-beta-String)


## `CHANGE SESSION`

[`Click Here For Change Session`](https://github.com/w5-bot-2/W5-BOT-beta/blob/master/session.json#L1)


## `Deploy`
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/w5-bot-2/W5-BOT-beta/)




# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor



## `ADD BUILDPACK`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

# Normal Installation
## Clone Repo & Installation dependencies
```bash
ð± git clone https://github.com/w5-bot-2/W5-BOT-beta.git
ð± cd W5-BOT-beta
ð± npm start
```
## For Termux
```bash
ð± apt update
ð± apt upgrade
ð± pkg update && pkg upgrade 
ð± pkg install bash
ð± pkg install libwebp
ð± pkg install git -y
ð± pkg install nodejs -y 
ð± pkg install ffmpeg -y 
ð± pkg install wget
ð± pkg install imagemagick -y
ð± git clone https://github.com/w5-bot-2/W5-BOT-beta
ð± cd W5-BOT-beta
ð± ls
ð± rm -rf session.json
ð± npm install
ð± npm start
ð± scan qr code within 15seconds
```

