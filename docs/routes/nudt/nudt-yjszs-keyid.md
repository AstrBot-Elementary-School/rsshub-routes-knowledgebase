# 中国人民解放军国防科技大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nudt`
- Namespace Name: `中国人民解放军国防科技大学`
- Route Path: `/nudt/yjszs/:keyId?`
- Route Name: `研究生院`
- Example: `/nudt/yjszs/2`
- URL: `yjszs.nudt.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Blank0120`
- Source Location: `yjszs.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 首页 | 招生简章 | 学校政策 | 硕士招生 | 博士招生 | 院所发文 | 数据统计 |
| -------- | ---- | -------- | -------- | -------- | -------- | -------- | -------- |
| 2        | 1    | 8        | 12       | 16       | 17       | 23       | 25       |

## Parameters
- `keyId`: 分类，见下表，默认为通知公告


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
  - `yjszs.nudt.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 首页 | 招生简章 | 学校政策 | 硕士招生 | 博士招生 | 院所发文 | 数据统计 |\n| -------- | ---- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 2        | 1    | 8        | 12       | 16       | 17       | 23       | 25       |",
  "example": "/nudt/yjszs/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "yjszs.ts",
  "maintainers": [
    "Blank0120"
  ],
  "name": "研究生院",
  "parameters": {
    "keyId": "分类，见下表，默认为通知公告"
  },
  "path": "/yjszs/:keyId?",
  "radar": [
    {
      "source": [
        "yjszs.nudt.edu.cn"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "国防科技大学研究生院 - 通知公告 - Powered by RSSHub",
      "errorAt": "2026-08-15T12:14:08.904Z",
      "errorMessage": "200 ",
      "id": "72564096646971392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yjszs.nudt.edu.cn/pubweb/homePageList/searchContent.view",
      "title": "国防科技大学研究生院 - 通知公告",
      "type": "feed",
      "url": "rsshub://nudt/yjszs/2"
    }
  ],
  "url": "yjszs.nudt.edu.cn/"
}
```
