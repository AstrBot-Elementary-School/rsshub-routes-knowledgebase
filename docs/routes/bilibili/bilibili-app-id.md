# 哔哩哔哩 bilibili - 更新情报

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/app/:id?`
- Route Name: `更新情报`
- Example: `/bilibili/app/android`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `app.ts`
- Source Module: `_None_`

## Description
| 安卓版  | iPhone 版 | iPad HD 版 | UWP 版 | TV 版            |
| ------- | --------- | ---------- | ------ | ---------------- |
| android | iphone    | ipad       | win    | android\_tv\_yst |

## Parameters
- `id`: 客户端 id，见下表，默认为安卓版


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
    "program-update"
  ],
  "description": "| 安卓版  | iPhone 版 | iPad HD 版 | UWP 版 | TV 版            |\n| ------- | --------- | ---------- | ------ | ---------------- |\n| android | iphone    | ipad       | win    | android\\_tv\\_yst |",
  "example": "/bilibili/app/android",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "app.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "更新情报",
  "parameters": {
    "id": "客户端 id，见下表，默认为安卓版"
  },
  "path": "/app/:id?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "哔哩哔哩更新情报 - 安卓版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150446950684260352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.bilibili.com/",
      "title": "哔哩哔哩更新情报 - 安卓版",
      "type": "feed",
      "url": "rsshub://bilibili/app"
    },
    {
      "description": "哔哩哔哩更新情报 - 安卓版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126248708971069440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.bilibili.com/",
      "title": "哔哩哔哩更新情报 - 安卓版",
      "type": "feed",
      "url": "rsshub://bilibili/app/android"
    }
  ]
}
```
