twdl
====

Twitter/X video downloader.

yt-dlp works only if given cookie. this utilizes fxtwitter so it works without cookie.

## Demo

```shell
❯ yt-dlp 'https://x.com/gemiko_voice/status/2049482670644908070'
[twitter] Extracting URL: https://x.com/gemiko_voice/status/2049482670644908070
[twitter] 2049482670644908070: Downloading guest token
[twitter] 2049482670644908070: Downloading GraphQL JSON
ERROR: [twitter] 2049482670644908070: No video could be found in this tweet
❯ twdl 'https://x.com/gemiko_voice/status/2049482670644908070'
fetching webpage.. done
https://video.twimg.com/amplify_video/2049482652802306048/vid/avc1/960x960/Bcj8RtTt2PGkAOHW.mp4?tag=21
```

## todo

- [ ] support gif

## license

GLWTPL
