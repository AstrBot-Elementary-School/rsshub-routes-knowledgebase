# Shanghai Museum - News & Announcements

## Coverage
`index-only`

## Route
- Namespace: `shanghaimuseum`
- Namespace Name: `Shanghai Museum`
- Route Path: `/shanghaimuseum/information/news/:type?`
- Route Name: `News & Announcements`
- Example: `/shanghaimuseum/information/news/all`
- URL: `www.shanghaimuseum.net`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: News type, supported values: all (新闻与公告) | news (新闻动态) | bulletin (本馆公告) | finance (财务公开). Default: all.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shanghaimuseum.net/mu/frontend/pg/infomation/news`
- `target`: `/information/news`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/shanghaimuseum/information/news/all",
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "News & Announcements",
  "parameters": {
    "type": "News type, supported values: all (新闻与公告) | news (新闻动态) | bulletin (本馆公告) | finance (财务公开). Default: all."
  },
  "path": "/information/news/:type?",
  "radar": [
    {
      "source": [
        "www.shanghaimuseum.net/mu/frontend/pg/infomation/news"
      ],
      "target": "/information/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海博物馆 - 新闻与公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1153239806356881408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.shanghaimuseum.net/mu/frontend/pg/infomation/news?type=all",
      "title": "上海博物馆 - 新闻与公告",
      "type": "feed",
      "url": "rsshub://shanghaimuseum/information/news/all"
    }
  ]
}
```
