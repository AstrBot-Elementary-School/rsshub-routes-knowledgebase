# CNCF - Category

## Coverage
`index-only`

## Route
- Namespace: `cncf`
- Namespace Name: `CNCF`
- Route Path: `/cncf/:cate?`
- Route Name: `Category`
- Example: `/cncf`
- URL: `cncf.io`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Blog | News | Announcements | Reports |
| ---- | ---- | ------------- | ------- |
| blog | news | announcements | reports |

## Parameters
- `cate`: blog by default


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
    "programming"
  ],
  "description": "| Blog | News | Announcements | Reports |\n| ---- | ---- | ------------- | ------- |\n| blog | news | announcements | reports |",
  "example": "/cncf",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 150,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Category",
  "parameters": {
    "cate": "blog by default"
  },
  "path": "/:cate?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CNCF - Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65418327052688384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cncf.io/blog/",
      "title": "CNCF - Blog",
      "type": "feed",
      "url": "rsshub://cncf"
    },
    {
      "description": "CNCF - Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56437982106136576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cncf.io/blog/",
      "title": "CNCF - Blog",
      "type": "feed",
      "url": "rsshub://cncf/blog"
    }
  ]
}
```
