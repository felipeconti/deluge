# deluge

## Docker for deluge

### Build
```sh
docker build -t deluge .
```

### Run
```sh
docker run -d --restart=always -v /home/felipe/config/:/config -v /home/felipe/hd/:/data -p 58846:58846 -p 80:8112 --name=deluge felipeconti/deluge
```
