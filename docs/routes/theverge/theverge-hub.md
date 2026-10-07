# The Verge - Category

## Coverage
`index-only`

## Route
- Namespace: `theverge`
- Namespace Name: `The Verge`
- Route Path: `/theverge/:hub?`
- Route Name: `Category`
- Example: `/theverge`
- URL: `theverge.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW, vbali`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Hub            | Hub name       |
| -------------- | -------------- |
|                | All Posts      |
| amazon         | Amazon         |
| android        | Android        |
| apple          | Apple          |
| apps           | Apps           |
| blackberry     | BlackBerry     |
| business       | Business       |
| creators       | Creators       |
| culture        | Culture        |
| entertainment  | Entertainment  |
| film           | Film           |
| games          | Gaming         |
| google         | Google         |
| health         | Health         |
| meta           | Meta           |
| microsoft      | Microsoft      |
| music          | Music          |
| policy         | Policy         |
| reviews        | Reviews        |
| samsung        | Samsung        |
| science        | Science        |
| space          | Space          |
| streaming      | Streaming      |
| tech           | Tech           |
| transportation | Transportation |
| tv             | TV Shows       |
| web            | Web            |

Provides a better reading experience (full text articles) over the official one.

## Parameters
- `hub`: Hub, see below, All Posts by default


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
  - `theverge.com/:hub`
  - `theverge.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Hub            | Hub name       |\n| -------------- | -------------- |\n|                | All Posts      |\n| amazon         | Amazon         |\n| android        | Android        |\n| apple          | Apple          |\n| apps           | Apps           |\n| blackberry     | BlackBerry     |\n| business       | Business       |\n| creators       | Creators       |\n| culture        | Culture        |\n| entertainment  | Entertainment  |\n| film           | Film           |\n| games          | Gaming         |\n| google         | Google         |\n| health         | Health         |\n| meta           | Meta           |\n| microsoft      | Microsoft      |\n| music          | Music          |\n| policy         | Policy         |\n| reviews        | Reviews        |\n| samsung        | Samsung        |\n| science        | Science        |\n| space          | Space          |\n| streaming      | Streaming      |\n| tech           | Tech           |\n| transportation | Transportation |\n| tv             | TV Shows       |\n| web            | Web            |\n\nProvides a better reading experience (full text articles) over the official one.",
  "example": "/theverge",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 310,
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "vbali"
  ],
  "name": "Category",
  "parameters": {
    "hub": "Hub, see below, All Posts by default"
  },
  "path": "/:hub?",
  "radar": [
    {
      "source": [
        "theverge.com/:hub",
        "theverge.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Apps | The Verge - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52982633246101506",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theverge.com/apps",
      "title": "Apps | The Verge",
      "type": "feed",
      "url": "rsshub://theverge/apps"
    },
    {
      "description": "The Verge - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56165613279845376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theverge.com/",
      "title": "The Verge",
      "type": "feed",
      "url": "rsshub://theverge"
    }
  ]
}
```
