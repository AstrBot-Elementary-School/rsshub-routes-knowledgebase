# 中国科技网 - 科技日报

## Coverage
`index-only`

## Route
- Namespace: `stdaily`
- Namespace Name: `中国科技网`
- Route Path: `/stdaily/digitalpaper`
- Route Name: `科技日报`
- Example: `/stdaily/digitalpaper`
- URL: `epaper.stdaily.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `lyqluis, KarasuShin`
- Source Location: `digitalpaper.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `epaper.stdaily.com/statics/technology-site/index.html`
- `target`: `/digitalpaper`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/stdaily/digitalpaper",
  "features": {
    "supportRadar": true
  },
  "heat": 86,
  "location": "digitalpaper.tsx",
  "maintainers": [
    "lyqluis",
    "KarasuShin"
  ],
  "name": "科技日报",
  "path": "/digitalpaper",
  "radar": [
    {
      "source": [
        "epaper.stdaily.com/statics/technology-site/index.html"
      ],
      "target": "/digitalpaper"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国科技网 - 科技日报 - Powered by RSSHub",
      "errorAt": "2026-08-03T06:09:50.319Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 63118600077338629",
      "id": "63118600077338629",
      "image": "https://www.stdaily.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://epaper.stdaily.com/",
      "title": "中国科技网 - 科技日报",
      "type": "feed",
      "url": "rsshub://stdaily/digitalpaper"
    }
  ]
}
```
