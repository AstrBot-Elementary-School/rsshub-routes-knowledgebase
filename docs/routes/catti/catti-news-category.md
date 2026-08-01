# 全国翻译专业资格水平考试 (CATTI) - CATTI 考试消息

## Coverage
`index-only`

## Route
- Namespace: `catti`
- Namespace Name: `全国翻译专业资格水平考试 (CATTI)`
- Route Path: `/catti/news/:category`
- Route Name: `CATTI 考试消息`
- Example: `/catti/news/zxzc`
- URL: `www.catticenter.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Category | 标题     | 描述                 |
| -------- | -------- | -------------------- |
| ggl      | 通知公告 | CATTI 考试通知和公告 |
| ywdt     | 要闻动态 | CATTI 考试要闻动态   |
| zxzc     | 最新政策 | CATTI 考试最新政策   |

## Parameters
- `category`: 消息分类名，可在下面的描述中找到。


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.catticenter.com/:category`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| Category | 标题     | 描述                 |\n| -------- | -------- | -------------------- |\n| ggl      | 通知公告 | CATTI 考试通知和公告 |\n| ywdt     | 要闻动态 | CATTI 考试要闻动态   |\n| zxzc     | 最新政策 | CATTI 考试最新政策   |",
  "example": "/catti/news/zxzc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 6,
  "location": "news.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "CATTI 考试消息",
  "parameters": {
    "category": "消息分类名，可在下面的描述中找到。"
  },
  "path": "/news/:category",
  "radar": [
    {
      "source": [
        "www.catticenter.com/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CATTI 考试通知和公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101927725498470400",
      "image": "https://www.catticenter.com/img/applogo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.catticenter.com/ggl",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://catti/news/ggl"
    },
    {
      "description": "CATTI 考试要闻动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101928092390409216",
      "image": "https://www.catticenter.com/img/applogo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.catticenter.com/ywdt",
      "title": "要闻动态",
      "type": "feed",
      "url": "rsshub://catti/news/ywdt"
    }
  ]
}
```
