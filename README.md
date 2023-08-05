The docker compose is used to make a streaming server based on all mp4 fuils in ./videos and a usb web camera.

1. put `.mp4` to ./videos/
2. run `docker compose up -d` and get rtsp from `rtsp://localhost:8554/{FILE_NAME_WITHOUT_EXTENSION}`