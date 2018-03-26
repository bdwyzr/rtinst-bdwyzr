# rtinst



## Installation

```
bash -c "$(wget --no-check-certificate -qO- https://raw.githubusercontent.com/Aniverse/rtinst/master/rtsetup)"
```
```
rtinst -tfylmi -v $rtorrentVERSION -u $USERNAME -p $PASSWORD -w $WEBPASSWORD 
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

Eg.  `rtinst -tfylmi -v 0.9.4 -u aniverse -p flood233 -w 12345678`  




## Modifications

- **New Opinions**  
Enable IPv6 when using -i opinion  
Set FTP port to 21 when using -f opinion  
Do NOT change SSH port but not sets it to 22 when using -t opinion  
Change the rtorrent version to be installed by using -v opinion  

- **ruTorrent plugins and themes**  
Install club-QuickBox theme  
Install MaterialDesign theme  
Install Filemanager plugin  
Install Fileshare plugin  
Install Mediastream plugin  
Install sox for ruTorrent spectrogram plugin  
Enable m2ts support for screenshots plugin  
Set SCGIServerTimeout to 60 for ruTorrent  
Fix AutoDL-Irssi issue on Ubuntu 16.04  

- **Install h5ai as file indexer**  
- **Install ffmpeg 3.4.52 from static builds**  
- **Install rar, unrar 5.5.0 (force)**  

- **Enable rTorrent logging**  
- **Tweak rTorrent default settings**  
- **Do NOT disable root login**  
- **Do NOT disable vsftpd IPv6 listen**  
- **Raised open file limits to 666666**  
- **To be added ...**  




## Guides

[The original README](https://github.com/arakasi72/rtinst/blob/master/README.md)  
[The detailed user guide](https://github.com/arakasi72/rtinst/wiki/Guide)  
[The detailed installation guide](https://github.com/arakasi72/rtinst/wiki/Installing-rtinst)  
[License](https://github.com/arakasi72/rtinst/blob/master/LICENSE)  
