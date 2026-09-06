# 电子科技大学 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/uestc/news/:type?`
- Route Name: `新闻中心`
- Example: `/uestc/news/culture`
- URL: `news.uestc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `achjqz, mobyw`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 学术    | 文化    | 公告         | 校内通知     |
| ------- | ------- | ------------ | ------------ |
| academy | culture | announcement | notification |

## Parameters
- `type`: 默认为 `announcement`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.uestc.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学术    | 文化    | 公告         | 校内通知     |\n| ------- | ------- | ------------ | ------------ |\n| academy | culture | announcement | notification |",
  "example": "/uestc/news/culture",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "news.ts",
  "maintainers": [
    "achjqz",
    "mobyw"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": "默认为 `announcement`"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "news.uestc.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "电子科技大学新闻网信息公告 - Powered by RSSHub",
      "errorAt": "2026-01-31T13:40:31.330Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "162691207633094656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.uestc.edu.cn/",
      "title": "新闻网通知",
      "type": "feed",
      "url": "rsshub://uestc/news/announcement"
    },
    {
      "description": "电子科技大学新闻网信息公告 - Powered by RSSHub",
      "errorAt": "2026-01-31T12:54:31.957Z",
      "errorMessage": "Failed to fetch\n",
      "id": "162691575957116928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.uestc.edu.cn/",
      "title": "新闻网通知",
      "type": "feed",
      "url": "rsshub://uestc/news/culture"
    }
  ],
  "url": "news.uestc.edu.cn/"
}
```
