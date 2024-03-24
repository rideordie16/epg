# TV

This is an IPTV playlist and EPG generator. On a scheduled run (hourly):

1. Fetches a public IPTV list
2. Filters out with a white list
3. Appends custom channels
4. Generates `playlist.m3u` and `channels.xml` files
5. Generates EPG information (`guide.xml`) using `channels.xml` file
6. Commits and pushes the changes

## Usage 

Updated playlist and guide files are found under `bin` directory. Use the following links in your favorite IPTV application:

#### Playlist:
```
https://raw.githubusercontent.com/ghokun/tv/main/bin/playlist.m3u
```
#### EPG:
```
https://raw.githubusercontent.com/ghokun/tv/main/bin/guide.xml
```
