# M3u8-URL-Extractor-from-Live-Server
This is a Linux Bash Script that will automatically extract hidden m3u8 url from Live TV server<br>
and Update the extracted m3u Playlist and upload to Github in every 1 hour automatically by cronjob.<br>

Free IPTV M3U Playlist 2020 Hourly Update with 76 Channels (Bangladesh, India, and International) [ Every 1 Hour Update Period] <br>

At first install httrack by running this command
```
sudo apt install httrack

```
Then Run the shell script
```
sh extract.sh
```
A m3u Playlist named IPTV.m3u will be generated in the same folder

Open Cronjob

```
crontab -e
```

Add this Cronjob

```
0 */1 * * * sh ~/scripts/extract.sh
```

