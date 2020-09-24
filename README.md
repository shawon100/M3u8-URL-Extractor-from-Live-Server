# M3u8-URL-Extractor-from-Live-Server
This is a Linux Bash Script that will automatically extract hidden m3u8 url from Live TV server <br>
and Updated the extracted m3u Playlist and uploaded to Github in every 10 minutes by cronjob

At first install httrack by running this command
```
sudo apt install httrack

```
Then Run the shell script
```
sh extract.sh
```
A m3u Playlist named IPTV.m3u will be generated in the same folder.

Cronjob

```
*/10 * * * * sh ~/scripts/extract.sh
```
