# 少数派 sspai - 标签订阅

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/tag/:keyword`
- Route Name: `标签订阅`
- Example: `/sspai/tag/apple`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Jeason0228`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词


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
  - `sspai.com/tag/:keyword`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/tag/apple",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 539,
  "location": "tag.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "标签订阅",
  "parameters": {
    "keyword": "关键词"
  },
  "path": "/tag/:keyword",
  "radar": [
    {
      "source": [
        "sspai.com/tag/:keyword"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Obsidian 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64601197070503936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://beta.sspai.com/tag/Obsidian",
      "title": "#Obsidian - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/tag/Obsidian"
    },
    {
      "description": "本周看什么 更新推送 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56232529208193024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://beta.sspai.com/tag/%E6%9C%AC%E5%91%A8%E7%9C%8B%E4%BB%80%E4%B9%88",
      "title": "#本周看什么 - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/tag/%E6%9C%AC%E5%91%A8%E7%9C%8B%E4%BB%80%E4%B9%88"
    }
  ]
}
```
