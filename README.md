# Scalingo Mirror Leech BOT
### This repo is lite version of <a href="https://github.com/anasty17/mirror-leech-telegram-bot">MLTB</a>

1. fill config.env on gist <br>
2. use this template make private repo <br>
3. add accounts folder and token.pickle <br>

### Tutorial:
[Watch the video](https://youtu.be/43G2AO8569M)
### Note: 
- Aria2p is removed so leech/mirror for direct links and magnets will not work <br>
btw you can leech from google drive

### Features:
- Log channel support
- Change filename while cloning, ex: `/clone <drive_url> |new file name.ext`
- Leech drive links (splitting, thumbnail for each user, setting as document or as media for each user)
- Stop duplicates for all tasks except yt-dlp tasks
- Zip/Unzip G-Drive links
- Counting files/folders from Google Drive link
- Direct Clone from 
  > GDToT, AppDrive, DriveApp, DriveLinks, DriveAce, DriveBit, DriveSharer, GDFlix, DriveRoot, DriveFlix, DriveHub.in, AniDrive, IndiDrive, HubDrive, KatDrive, DriveHub.ws, Kolop, DriveFire, DriveBuzz and Sharer.pw links
- View Link button, extra button to open file index link in broswer instead of direct download
- Status Pages for unlimited tasks
- Clone status
- Search in multiple Drive folder/TeamDrive
- Recursive Search (only with `root` or TeamDrive ID, folder ids will be listed with non-recursive method)
- Multi-TD list by token.pickle if exists
- Extract rar, zip and 7z splits with or without password
- Zip file/folder with or without password
- Use Token.pickle if file not found with Service Account for all Gdrive functions
- Random Service Account at startup
- Mirror/Leech/Watch/Clone/Count/Del by reply
- YT-DLP quality buttons
- Extenstion Filter for uploading/cloning files
- Incomplete task notifier to get incomplete task messages after restart, works with database.
- Mirror Telegram files to Google Drive
- Copy files from someone's Drive to your Drive
- Download/Upload progress, Speeds and ETAs
- Mirror all yt-dlp supported links
- Uploading to Team Drive
- Index Link support
- Service Account support
- Delete files from Drive
- Add sudo users
- Custom Filename* (Only for Telegram files and yt-dlp)
- Extract password protected files
- Extract these filetypes and uploads to Google Drive
  > ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, NTFS, RPM, SquashFS, UDF, VHD, XAR, Z, TAR.XZ

#Bot Commands:
```
start - Check Online
mirror - Mirror
leech - Leech
zipmirror - Mirror and upload as zip
unzipmirror - Mirror and extract files
qbmirror - Mirror torrent using qBittorrent
qbzipmirror - Mirror torrent and upload as zip using qb
qbunzipmirror - Mirror torrent and extract files using qb
zipleech - Leech and upload as zip
unzipleech - Leech and extract files
qbleech - Leech torrent using qBittorrent
qbzipleech - Leech torrent and upload as zip using qb
qbunzipleech - Leech torrent and extract using qb
clone - Copy file/folder to Drive
count - Count file/folder of Drive
watch - Mirror yt-dlp supported link
zipwatch - Mirror yt-dlp supported link as zip
leechwatch - Leech through yt-dlp supported link
leechzipwatch - Leech yt-dlp support link as zip
leechset - Leech settings
setthumb - Set thumbnail
status - Get Mirror Status message
list - Search files in Drive
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

# Modified By:
Yash Oswal (https://github.com/yashoswalyo) <br>
Majnu Rangeela (https://github.com/majnurangeela)
