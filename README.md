# rtinst



## Installation

```
bash -c "$(wget --no-check-certificate -qO- https://raw.githubusercontent.com/Aniverse/rtinst/master/rtsetup)"
```
```
rtinst -$opinions -v $rtorrentVERSION -u $USERNAME -p $PASSWORD -w $WEBPASSWORD 
```
```
rtinst -tfylmi -v 0.9.4 -u aniverse -p kinots74212 -w rutmypa44  
```

- `-t` Do NOT change SSH port  
- `-f` Set FTP port to 21  
- `-y` Force yes to all the questions  
- `-l` Enable logging to ~/rtinst.log  
- `-m` Install the latest master build of rutorrent  
- `-i` Enable IPv6 for rTorrent and libtorrent-rakshasa  
- `-u` Name the user to be primary rtorrent user  
- `-p` Set the unix password  
- `-w` Set the web password for the user  
- `-v` Set the rTorrent version you would like to be installed  





## Modifications

- **New Opinions**  
Using `-i` opinion to enable IPv6 support  
Using `-f` opinion to set FTP port to 21  
Using `-t` opinion to keep the old SSH port  
Using `-v` opinion to select the rtorrent version to be installed  

- **ruTorrent plugins and themes**  
Install club-QuickBox theme  
Install MaterialDesign theme  
Install Filemanager plugin  
Install Fileshare plugin  
Install Mediastream plugin  
Install sox for ruTorrent spectrogram plugin  
Enable m2ts support for screenshots plugin  
Set SCGIServerTimeout to 60  
Fix AutoDL-Irssi issue on Ubuntu 16.04  

- **Install h5ai as file indexer**  
- **Install ffmpeg 4.0.2 from static builds**  
- **Install rar, unrar 5.6.1**  
- **Enable rTorrent logging**  
- **Tweak rTorrent default settings**  
- **Do NOT disable root login**  
- **Raised open file limits to 666666**  

- **Setup Nginx Reverse Proxy for Deluge, qBittorrent, Transmission, Flood and Flexget**  

- **To be added ...**  




## Guides

[The original README](https://github.com/arakasi72/rtinst/blob/master/README.md)  
[The detailed user guide](https://github.com/arakasi72/rtinst/wiki/Guide)  
[The detailed installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)  
[License](https://github.com/arakasi72/rtinst/blob/master/LICENSE)  
