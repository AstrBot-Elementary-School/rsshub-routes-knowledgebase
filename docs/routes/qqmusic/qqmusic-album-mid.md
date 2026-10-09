# QQ 音乐 - 专辑节目更新

## Coverage
`index-only`

## Route
- Namespace: `qqmusic`
- Namespace Name: `QQ 音乐`
- Route Path: `/qqmusic/album/:mid`
- Route Name: `专辑节目更新`
- Example: `/qqmusic/album/001N8TFz49WZol`
- URL: `y.qq.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `album.ts`
- Source Module: `_None_`

## Description
Lists episodes in the source’s newest-first order. Includes public metadata and episode links; playback follows QQ Music’s access requirements.

## Parameters
- `mid`: Album ID from the website URL.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `y.qq.com/n/ryqq/albumDetail/:mid`
- `target`: `/album/:mid`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Lists episodes in the source’s newest-first order. Includes public metadata and episode links; playback follows QQ Music’s access requirements.",
  "example": "/qqmusic/album/001N8TFz49WZol",
  "heat": 0,
  "location": "album.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "专辑节目更新",
  "parameters": {
    "mid": "Album ID from the website URL."
  },
  "path": "/album/:mid",
  "radar": [
    {
      "source": [
        "y.qq.com/n/ryqq/albumDetail/:mid"
      ],
      "target": "/album/:mid"
    }
  ],
  "topFeeds": []
}
```
