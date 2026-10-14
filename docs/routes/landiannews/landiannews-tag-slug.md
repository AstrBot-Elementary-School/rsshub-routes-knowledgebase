# 蓝点网 - 标签

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/landiannews/tag/:slug`
- Route Name: `标签`
- Example: `/landiannews/tag/linux-kernel`
- URL: `www.landiannews.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `cscnk52`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 标签名称


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
  - `www.landiannews.com/archives/tag/:slug`
- `target`: `/tag/:slug`
### Rule 2
- `source`:
  - `www.landian.news/archives/tag/:slug`
- `target`: `/tag/:slug`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews/tag/linux-kernel",
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
  "location": "tag.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "标签",
  "parameters": {
    "slug": "标签名称"
  },
  "path": "/tag/:slug",
  "radar": [
    {
      "source": [
        "www.landiannews.com/archives/tag/:slug"
      ],
      "target": "/tag/:slug"
    },
    {
      "source": [
        "www.landian.news/archives/tag/:slug"
      ],
      "target": "/tag/:slug"
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
