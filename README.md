# VideoBackgroud

A video.js powered player meant to be used as background video player. Can be used as is or with an iframe.

## Usage

Use following url format to play video in iframe

http://example.com/player.html?id=btoa('videoUrl')

For example : http://127.0.0.1:5500/player.html?vid=aHR0cDovL2NvbW1vbmRhdGFzdG9yYWdlLmdvb2dsZWFwaXMuY29tL2d0di12aWRlb3MtYnVja2V0L3NhbXBsZS9CaWdCdWNrQnVubnkubXA0

### Options

Url supports following parameters
| Key | Required | Value |
|--|--|--|
| vid | Yes | Base64 encoded video url
| poster | No | Videojs poster ([more info](https://docs.videojs.com/posterimage))
|volume| No | Any value in range 0 to 1 (Defaults to 0)
