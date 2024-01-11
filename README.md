# Snapcast/Mopidy/Shairport-Sync Setup

Source on GitHub: [https://github.com/mcb/streaming-audio](https://github.com/streaming-audio)  
Image on GitHub Container Registry: [ghcr.io/mcb/streaming-audio-mopidy](https://ghcr.io/mcb/streaming-audio-mopidy) and [ghcr.io/mcb/streaming-audio-snapserver](https://ghcr.io/mcb/streaming-audio-snapserver). This project uses the official docker image from [https://github.com/mikebrady/shairport-sync-docker](https://github.com/mikebrady/shairport-sync-docker).

Major image tags:
- `latest`
- `dev`


### In a Nutshell
[Snapcast](https://github.com/badaix/snapcast) multi-room audio streaming with AirPlay-2 and Mopidy support built-in. Based on Alpine Linux.

Snapcast/Mopidt are loaded from the edge branch of Alpines APK repositories while `shairport-sync` uses the official docker image. 
