# M3u8-URL-Extractor-from-Live-Server
This is a Linux Bash Script that will automatically extract hidden m3u8 url from Live TV server<br>
and Update the extracted m3u Playlist and upload to Github in every 50 minutes automatically by cronjob

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
*/50 * * * * sh ~/scripts/extract.sh
```
