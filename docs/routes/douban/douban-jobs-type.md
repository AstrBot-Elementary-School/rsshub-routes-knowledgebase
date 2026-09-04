# 豆瓣 - 豆瓣招聘

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/jobs/:type`
- Route Name: `豆瓣招聘`
- Example: `/douban/jobs/campus`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Fatpandac`
- Source Location: `other/jobs.ts`
- Source Module: `_None_`

## Description
| 社会招聘 | 校园招聘 | 实习生招聘 |
| :------: | :------: | :--------: |
|  social  |  campus  |   intern   |

## Parameters
- `type`: 招聘类型，见下表


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
  "description": "| 社会招聘 | 校园招聘 | 实习生招聘 |\n| :------: | :------: | :--------: |\n|  social  |  campus  |   intern   |",
  "example": "/douban/jobs/campus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "other/jobs.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "豆瓣招聘",
  "parameters": {
    "type": "招聘类型，见下表"
  },
  "path": "/jobs/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣社会招聘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64631344706970624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jobs.douban.com/jobs/social",
      "title": "豆瓣社会招聘",
      "type": "feed",
      "url": "rsshub://douban/jobs/social"
    }
  ]
}
```
