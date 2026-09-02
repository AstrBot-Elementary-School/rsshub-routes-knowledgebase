# Bangumi 番组计划 - 小组话题

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/group/:id`
- Route Name: `小组话题`
- Example: `/bangumi.tv/group/boring`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SettingDust`
- Source Location: `group/topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小组 id, 在小组页面地址栏查看


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
  - `bgm.tv/group/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/group/boring",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 60,
  "location": "group/topic.ts",
  "maintainers": [
    "SettingDust"
  ],
  "name": "小组话题",
  "parameters": {
    "id": "小组 id, 在小组页面地址栏查看"
  },
  "path": "/group/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/group/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Bangumi - Bangumi半月刊 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87726938189788160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/group/biweekly/forum",
      "title": "Bangumi - Bangumi半月刊",
      "type": "feed",
      "url": "rsshub://bangumi.tv/group/biweekly"
    },
    {
      "description": "Bangumi - 靠谱人生茶话会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72563300550000640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/group/boring/forum",
      "title": "Bangumi - 靠谱人生茶话会",
      "type": "feed",
      "url": "rsshub://bangumi.tv/group/boring"
    }
  ]
}
```
