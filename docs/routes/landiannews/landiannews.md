# 蓝点网 - 首页

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/landiannews/`
- Route Name: `首页`
- Example: `/landiannews`
- URL: `www.landiannews.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, cscnk52`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.landiannews.com`
- `target`: `/`
### Rule 2
- `source`:
  - `www.landian.news`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "cscnk52"
  ],
  "name": "首页",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.landiannews.com"
      ],
      "target": "/"
    },
    {
      "source": [
        "www.landian.news"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.landiannews.com",
  "view": 0
}
```
