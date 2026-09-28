# 天下雜誌 - 子頻道

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/sub/:channel`
- Route Name: `子頻道`
- Example: `/cw/sub/615`
- URL: `cw.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `sub.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 子頻道 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/sub/615",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sub.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "子頻道",
  "parameters": {
    "channel": "子頻道 ID，可在 URL 中找到"
  },
  "path": "/sub/:channel",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
