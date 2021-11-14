# ffmpeg-rtsp-pusher

## Build
```sh
sudo ./build.sh
```

## Depoly
```sh
sudo docker run -d --name=ffmpeg-rtsp-pusher --restart=always -e "RTSP_SERVER=${EasyDarwin_Host}" mmdjiji/ffmpeg-rtsp-pusher
```
