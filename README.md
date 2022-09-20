# Notes

## command
```
# start server
docker compose up -d
# then visit localhost:5080, create initialize login account

# stop and rm server
docker compose down
```

## live
setup live stream or playlist in LiveApp, then you will get an id;

access LiveApp play.html with id (http://localhost:5080/LiveApp/play.html?id=mp4video)

### playlist
playlist seems only support pulling mp4 from http server, cannot load local mp4 file;

upload mp4 to nginx folder, then you can access them from ant media server by url syntax "http://nginx/YOUR_MP4_FILE"

### stream source
support m3u8 (youtube, twitch), not mpd (facebook)
