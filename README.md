# SSTV-playlist
Generate a M3U8 playlist from an authenticated [SmoothStreamsTV URL](http://streamtvnow.tv/players/web_auth_old/index.php).  No affiliation with SmoothStreamsTV or StreamTVNow.

This program will output an M3U8 playlist file when fed an authenticated URL.  

It simply extracts the auth token from the authenticated URL and inserts it into an m3u8 template with the channel names/URLs from StreamTVNow.

## Why did I build this?

#### The StreamTVNow interface leaves a lot to be desired...

![This is lame](old-interface.png)

#### VLC is my favourite media player.
...and it plays nicely with M3U8 playlists, including playlists of HLS streams.

## How do I use this?

#### 1. Sign in to your account on [StreamTVNow](http://streamtvnow.tv).

#### 2. Go to the []"old" player page](http://streamtvnow.tv/players/web_auth_old/index.php).

#### 3. Click on the VLC traffic cone icon, below the video player frame.

![VLC cone icon](click-on-vlc.png)

#### 4. Highlight and copy the link that appears beside the **HLS** box.

![Copy URL](copy-URL.png)

#### 5. Open a terminal or command line and run the python script.

![Run the script](run-script.png)

#### 6. Paste the URL from your clipboard into the terminal window.

![Paste the URL](paste-URL.png)
