```bash
ffmpeg -ss 00:00:00.30 -i originial.m4a -t 00:00:48.90 -acodec copy ok.m4a
ffmpeg -ss 00:00:00.30 -i originial.webm -t 00:00:48.90 -acodec copy ok.webm

ffmpeg -ss 00:00:15.18 -i originial.m4a -t 00:00:33.78 -acodec copy ring.m4a
ffmpeg -ss 00:00:15.18 -i originial.webm -t 00:00:33.78 -acodec copy ring.webm
```