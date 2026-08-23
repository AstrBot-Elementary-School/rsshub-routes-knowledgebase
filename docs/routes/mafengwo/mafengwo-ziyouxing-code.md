# 马蜂窝 - 自由行

## Coverage
`index-only`

## Route
- Namespace: `mafengwo`
- Namespace Name: `马蜂窝`
- Route Path: `/mafengwo/ziyouxing/:code`
- Route Name: `自由行`
- Example: `/mafengwo/ziyouxing/10186`
- URL: `www.mafengwo.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `nczitzk`
- Source Location: `ziyouxing.ts`
- Source Module: `_None_`

## Description
目的地代码请参见 [这里](http://www.mafengwo.cn/mdd/)

## Parameters
- `code`: 目的地代码，可在该目的地页面的 URL 中找到


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
    "travel"
  ],
  "description": "目的地代码请参见 [这里](http://www.mafengwo.cn/mdd/)",
  "example": "/mafengwo/ziyouxing/10186",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ziyouxing.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "自由行",
  "parameters": {
    "code": "目的地代码，可在该目的地页面的 URL 中找到"
  },
  "path": "/ziyouxing/:code",
  "topFeeds": []
}
```
