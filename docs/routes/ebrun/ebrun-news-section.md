# 亿邦动力 - 最新资讯和快讯

## Coverage
`index-only`

## Route
- Namespace: `ebrun`
- Namespace Name: `亿邦动力`
- Route Path: `/ebrun/news/:section?`
- Route Name: `最新资讯和快讯`
- Example: `/ebrun/news/information`
- URL: `www.ebrun.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: information：最新资讯（默认）；newest：快讯。


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `www.ebrun.com/information`
- `target`: `/news/information`
### Rule 2
- `source`:
  - `www.ebrun.com/newest`
- `target`: `/news/newest`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ebrun/news/information",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "最新资讯和快讯",
  "parameters": {
    "section": "information：最新资讯（默认）；newest：快讯。"
  },
  "path": "/news/:section?",
  "radar": [
    {
      "source": [
        "www.ebrun.com/information"
      ],
      "target": "/news/information"
    },
    {
      "source": [
        "www.ebrun.com/newest"
      ],
      "target": "/news/newest"
    }
  ],
  "topFeeds": []
}
```
