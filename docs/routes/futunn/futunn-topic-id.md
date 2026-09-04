# Futubull 富途牛牛 - 专题

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/futunn/topic/:id`
- Route Name: `专题`
- Example: `/futunn/topic/1267`
- URL: `news.futunn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `kennyfong19931`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Topic ID, can be found in URL


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/news-topics/:id/*`
  - `news.futunn.com/:lang/news-topics/:id/*`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/topic/1267",
  "features": {
    "supportRadar": true
  },
  "heat": 27,
  "location": "topic.ts",
  "maintainers": [
    "kennyfong19931"
  ],
  "name": "专题",
  "parameters": {
    "id": "Topic ID, can be found in URL"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "news.futunn.com/news-topics/:id/*",
        "news.futunn.com/:lang/news-topics/:id/*"
      ],
      "target": "/topic/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "富途牛牛 - 专题 - - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "212426851395679232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.futunn.com/news-topics/127/",
      "title": "富途牛牛 - 专题 -",
      "type": "feed",
      "url": "rsshub://futunn/topic/127"
    },
    {
      "description": "更多AI黑科技、场景落地、商用价值，尽在这里。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "233311236627653632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.futunn.com/news-topics/1267/",
      "title": "富途牛牛 - 专题 - 聚焦AI动向",
      "type": "feed",
      "url": "rsshub://futunn/topic/1267"
    }
  ]
}
```
