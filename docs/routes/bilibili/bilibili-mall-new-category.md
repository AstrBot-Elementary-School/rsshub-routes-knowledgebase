# 哔哩哔哩 bilibili - 会员购新品上架

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/mall/new/:category?`
- Route Name: `会员购新品上架`
- Example: `/bilibili/mall/new/1`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `mall-new.ts`
- Source Module: `_None_`

## Description
| 全部 | 手办 | 魔力赏 | 周边 | 游戏 |
| ---- | ---- | ------ | ---- | ---- |
| 0    | 1    | 7      | 3    | 6    |

## Parameters
- `category`: 分类，默认全部，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 全部 | 手办 | 魔力赏 | 周边 | 游戏 |\n| ---- | ---- | ------ | ---- | ---- |\n| 0    | 1    | 7      | 3    | 6    |",
  "example": "/bilibili/mall/new/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "mall-new.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "会员购新品上架",
  "parameters": {
    "category": "分类，默认全部，见下表"
  },
  "path": "/mall/new/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "会员购新品上架-手办 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337676",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mall.bilibili.com/newdate.html?noTitleBar=1&page=new&from=new_product&loadingShow=1",
      "title": "会员购新品上架-手办",
      "type": "feed",
      "url": "rsshub://bilibili/mall/new/1"
    },
    {
      "description": "会员购新品上架-全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60873113485072384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mall.bilibili.com/newdate.html?noTitleBar=1&page=new&from=new_product&loadingShow=1",
      "title": "会员购新品上架-全部",
      "type": "feed",
      "url": "rsshub://bilibili/mall/new"
    }
  ]
}
```
