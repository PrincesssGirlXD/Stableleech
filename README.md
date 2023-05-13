This is a Telegram Bot written in Python for mirroring files on the Internet to your Google Drive or Telegram. Based on [python-aria-mirror-bot](https://github.com/lzzy12/python-aria-mirror-bot)

# Features:

## If you Like My work Star the repo and Follow me on Github

# Features:
## By [The Immortal](https://github.com/PrincesssGirlXD)
- Mirror logs
- Leech logs
- Source link button
- Database Support for leech logs
- Sending Leeched files and Mirror links in user's PM
- Added Gdtot Support back
- Appdrive Support
- Change commands directly from config.env
- Auto Delete All Bot Related Message in AUTO_DELETE_UPLOAD_MESSAGE_DURATION duration
- View File in PM button
- Engine stats in status
- Statistics button in status
- 4 GB upload for Premium users
- BOT PM
- FORCE BOT PM
- Change Start buttons from config.env
- And many more little changes can't remember

### qBittorrent
- Qbittorrent support
- Select files from Torrent before and while downloading
- Seed torrents to specific ratio and time
### Aria2c
- Select files from Torrent before and while downloading
- Seed torrents to specific ratio and time
- Netrc support
- Direct link authentication for specific link while using the bot (it will work even if only username or password)
- Improve aria.sh
- Fix all download listener functions and status
### Leech
- Leech support
- Splitting
- Thumbnail for each user
- Set upload as document or as media for each user
### Google
- Stop duplicates for all tasks except yt-dlp tasks
- Download G-Drive links
- Counting files/folders from Google Drive link
- Search in multiple Drive folder/TeamDrive
- Recursive Search (only with `root` or TeamDrive ID, folder ids will be listed with non-recursive method)
- Use Token.pickle if file not found with Service Account, for all Gdrive functions
- List result in html file instead of telegraph or telegram message to avoid limits by @junedkh
- Random Service Account at startup
### Status
- Clone Status
- Extract Status
- Archive Status
- Seed Status
- Status Pages for unlimited tasks
- Ability to cancel upload/clone/archive/extract/split
- Cancel all buttons for choosing specific tasks status to cancel
- Fix flooding issues
- Fix overall upload and download speed
### Yt-dlp
- Switch from youtube-dl to yt-dlp and fix all conflicts
- Yt-dlp quality buttons
- Support for download live streams
- Ability to use specific yt-dlp arg for each task
- Fix download progress
### Database
- SQL Database support
- Save leech settings including thumbnails in database
- Save sudo and authorized users
- Incomplete task notifier to get incomplete task messages after restart
### Torrents Search
- Torrent search support
- Search on torrents with Torrent Search API
- Search on torrents with variable plugins using qBittorrent search engine
### Archives
- Zip instead of tar
- Using 7-zip tool to extract all supported files
- Extract rar, zip and 7z within folder or splits with or without password
- Zip file/folder with or without password
### RSS
- Rss feed. Based on this repository [rss-chan](https://github.com/hyPnOtICDo0g/rss-chan)
- Filter added and all functions have been improved
### Overall
- Docker image support for linux `amd64, arm64/v8, arm/v7, s390x`
- Update bot at startup and with restart command using `UPSTREAM_REPO`
- Mirror/Leech/Watch/Clone/Count/Del by reply
- Mirror/Leech/Clone multi links/files with one command
- Custom name for all links except torrents. For files you should add extension except yt-dlp links
- Extensions Filter for the files to be uploaded/cloned
- View Link button. Extra button to open index link in broswer instead of direct download for file
- Almost all repository functions have been improved and many other details can't mention all of them
- Many bugs have been fixed

## From Base and other Repositories
- Mirror direct download links, Torrent, Mega.nz and Telegram files to Google Drive
- Copy files from someone's Drive to your Drive
- Download/Upload progress, Speeds and ETAs
- Mirror all youtube-dl supported links
- Docker support
- Uploading to Team Drive
- Index Link support
- Service Account support
- Delete files from Drive
- Multiple Trackers support
- Shell and Executor
- Add sudo users
- Extract password protected files
- Extract these filetypes
  > ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, NTFS, RPM, SquashFS, UDF, VHD, XAR, Z, TAR.XZ
- Direct links Supported:
  >mediafire, letsupload.io, hxfile.co, anonfiles.com, bayfiles.com, antfiles, fembed.com, fembed.net, femax20.com, layarkacaxxi.icu, fcdn.stream, sbplay.org, naniplay.com, naniplay.nanime.in, naniplay.nanime.biz, sbembed.com, streamtape.com, streamsb.net, feurl.com, upload.ee, pixeldrain.com, racaty.net, 1fichier.com, 1drv.ms (Only works for file not folder or business account), uptobox.com and solidfiles.com

```
mirror -Mirror
zipmirror - Mirror and upload as zip
unzipmirror - Mirror and extract files
qbmirror - Mirror torrent using qBittorrent
qbzipmirror - Mirror torrent and upload as zip using qb
qbunzipmirror - Mirror torrent and extract files using qb
leech - Leech
zipleech - Leech and upload as zip
unzipleech - Leech and extract files
qbleech -  Leech torrent using qBittorrent
qbzipleech - Leech torrent and upload as zip using qb
qbunzipleech - Leech torrent and extract using qb
clone - Copy file/folder to Drive
count - Count file/folder of Drive
ytdl - Mirror yt-dlp supported link
ytdlzip -  Mirror yt-dlp supported link as zip
ytdlleech - Leech through yt-dlp supported link
ytdlzipleech - Leech yt-dlp support link as zip
leechset - Leech settings
setthumb - Set thumbnail
status - Get Mirror Status message
btsel - select files from torrent
rsslist -  List all subscribed rss feed info
rssget - Get specific No. of links from specific rss feed
rsssub - Subscribe new rss feed
rssunsub - Unsubscribe rss feed by title
rssset -  Rss Settings
list - Search files in Drive
search - Search for torrents with API
cancel - Cancel a task
cancelall - Cancel all tasks
del - Delete file/folder from Drive
log - Get the Bot Log
shell - Run commands in Shell
restart - Restart the Bot
stats - Bot Usage Stats
ping - Ping the Bot
help - All cmds with description
```