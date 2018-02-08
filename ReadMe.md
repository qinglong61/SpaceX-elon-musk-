### DownloadPath

> https://prod-video-us-west-1.pscp.tv/R9Xd0YeIvkdEnjHTjnmWExTjC2Zwuy8YlCOQmSP5Vq2GMHGDlcuMJzEaNg0SK0tYWk7VQF1qxw9yH7R90LMZCw/replay/us-west-1/periscope-replay-direct-prod-us-west-1-public/playlist_16928774065241509961.m3u8

### Convert CMD

```
cat *.ts > merged.ts
ffmpeg -i merged.ts converted.mp4
ffmpeg -i converted.mp4 -s 568x320 -r 10 animation.gif
ffmpeg -i merged.ts -ss 15 -t 0.001 screenshot.jpg
```