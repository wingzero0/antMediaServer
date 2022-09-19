#

command
```
# start server
./docker.sh
# then visit localhost:5080

# stop and rm server
docker stop antmedia
```

notes

setup live stream or playlist in LiveApp, then you will get an id;

access LiveApp play.html with id (http://localhost:5080/LiveApp/play.html?id=mp4video)

playlist seems only support pulling mp4 from http server, cannot load local mp4 file;
