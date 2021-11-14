FROM alfg/ffmpeg:latest
MAINTAINER JiJi <i@mmdjiji.com>
ENV TIME_ZONE=Asia/Shanghai
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app
WORKDIR /usr/src/app
CMD ffmpeg -re -i /usr/src/app/demo.mp4 -rtsp_transport tcp -vcodec h264 -f rtsp rtsp://${RTSP_SERVER}:8554/demo