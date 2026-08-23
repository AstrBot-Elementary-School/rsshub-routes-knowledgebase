# 少数派 sspai - 专题

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/topics`
- Route Name: `专题`
- Example: `/sspai/topics`
- URL: `sspai.com/topics`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `sunshinenny`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
此为专题广场更新提示 => 集合型而非单篇文章。与下方 "专题内文章更新" 存在明显区别！

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/topics`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "此为专题广场更新提示 => 集合型而非单篇文章。与下方 \"专题内文章更新\" 存在明显区别！",
  "example": "/sspai/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "topics.ts",
  "maintainers": [
    "sunshinenny"
  ],
  "name": "专题",
  "parameters": {},
  "path": "/topics",
  "radar": [
    {
      "source": [
        "sspai.com/topics"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "仅仅推送新的专题(集合型而非具体文章) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67411189738672128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/topics",
      "title": "少数派专题广场更新推送",
      "type": "feed",
      "url": "rsshub://sspai/topics"
    }
  ],
  "url": "sspai.com/topics"
}
```
