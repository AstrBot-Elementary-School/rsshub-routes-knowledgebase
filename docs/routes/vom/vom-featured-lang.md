# Voice of Mongolia - News

## Coverage
`index-only`

## Route
- Namespace: `vom`
- Namespace Name: `Voice of Mongolia`
- Route Path: `/vom/featured/:lang?`
- Route Name: `News`
- Example: `/vom/featured`
- URL: `vom.mn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `featured.ts`
- Source Module: `_None_`

## Description
| English | 日本語 | Монгол | Русский | 简体中文 |
| ------- | ------ | ------ | ------- | -------- |
| en      | ja     | mn     | ru      | zh       |

## Parameters
- `lang`: Language, see the table below, `mn` by default


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
  - `vom.mn/:lang`
  - `vom.mn/`
- `target`: `/featured/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| English | 日本語 | Монгол | Русский | 简体中文 |\n| ------- | ------ | ------ | ------- | -------- |\n| en      | ja     | mn     | ru      | zh       |",
  "example": "/vom/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "featured.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "lang": "Language, see the table below, `mn` by default"
  },
  "path": "/featured/:lang?",
  "radar": [
    {
      "source": [
        "vom.mn/:lang",
        "vom.mn/"
      ],
      "target": "/featured/:lang"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "VoM.mn - Voice of Mongolia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64309319450846208",
      "image": "http://www.vom.mn/dist/images/vom-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "VoM.mn - Voice of Mongolia",
      "type": "feed",
      "url": "rsshub://vom/featured"
    },
    {
      "description": "VoM.mn - Voice of Mongolia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "116831194976780288",
      "image": "http://www.vom.mn/dist/images/vom-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "VoM.mn - Voice of Mongolia",
      "type": "feed",
      "url": "rsshub://vom/featured/en"
    }
  ]
}
```
