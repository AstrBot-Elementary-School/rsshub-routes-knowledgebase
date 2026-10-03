# National Museum of Chinese Writing - 资讯

## Coverage
`index-only`

## Route
- Namespace: `wzbwg`
- Namespace Name: `National Museum of Chinese Writing`
- Route Path: `/wzbwg/news/:type`
- Route Name: `资讯`
- Example: `/wzbwg/news/24`
- URL: `www.wzbwg.com`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: News Type, supported values: 24（重要资讯）, 23（通知公告）, 25（工作动态）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wzbwg.com/news/:type`
- `target`: `/news/:type`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/wzbwg/news/24",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "资讯",
  "parameters": {
    "type": "News Type, supported values: 24（重要资讯）, 23（通知公告）, 25（工作动态）"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "www.wzbwg.com/news/:type"
      ],
      "target": "/news/:type"
    }
  ],
  "topFeeds": []
}
```
