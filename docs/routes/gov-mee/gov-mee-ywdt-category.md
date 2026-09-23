# 中华人民共和国生态环境部 - 要闻动态

## Coverage
`index-only`

## Route
- Namespace: `gov/mee`
- Namespace Name: `中华人民共和国生态环境部`
- Route Path: `/gov/mee/ywdt/:category?`
- Route Name: `要闻动态`
- Example: `/gov/mee/ywdt/hjywnews`
- URL: `www.mee.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `liuxsdev`
- Source Location: `ywdt.ts`
- Source Module: `_None_`

## Description
| 时政要闻 | 环境要闻 | 地方快讯 | 新闻发布 | 视频新闻 | 公示公告 |
| :------: | :------: | :------: | :------: | :------: | :------: |
|   szyw   | hjywnews |  dfnews  |   xwfb   |   spxw   |   gsgg   |

## Parameters
- `category`: 分类名，预设 `szyw`


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
  - `www.mee.gov.cn/ywdt/:category`
- `target`: `/ywdt/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 时政要闻 | 环境要闻 | 地方快讯 | 新闻发布 | 视频新闻 | 公示公告 |\n| :------: | :------: | :------: | :------: | :------: | :------: |\n|   szyw   | hjywnews |  dfnews  |   xwfb   |   spxw   |   gsgg   |",
  "example": "/gov/mee/ywdt/hjywnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "ywdt.ts",
  "maintainers": [
    "liuxsdev"
  ],
  "name": "要闻动态",
  "parameters": {
    "category": "分类名，预设 `szyw`"
  },
  "path": "/ywdt/:category?",
  "radar": [
    {
      "source": [
        "www.mee.gov.cn/ywdt/:category"
      ],
      "target": "/ywdt/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "环境要闻 - 要闻动态 - 中华人民共和国生态环境部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73652336403326987",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mee.gov.cn/ywdt/",
      "title": "环境要闻 - 要闻动态 - 中华人民共和国生态环境部",
      "type": "feed",
      "url": "rsshub://gov/mee/ywdt/hjywnews"
    },
    {
      "description": "公示公告 - 要闻动态 - 中华人民共和国生态环境部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131720350563788800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mee.gov.cn/ywdt/",
      "title": "公示公告 - 要闻动态 - 中华人民共和国生态环境部",
      "type": "feed",
      "url": "rsshub://gov/mee/ywdt/gsgg"
    }
  ]
}
```
