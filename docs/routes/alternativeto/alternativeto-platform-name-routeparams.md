# AlternativeTo - Platform Software

## Coverage
`index-only`

## Route
- Namespace: `alternativeto`
- Namespace Name: `AlternativeTo`
- Route Path: `/alternativeto/platform/:name/:routeParams?`
- Route Name: `Platform Software`
- Example: `/alternativeto/platform/firefox`
- URL: `www.alternativeto.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JimenezLi`
- Source Location: `platform.ts`
- Source Module: `_None_`

## Description
> routeParms can be copied from original site URL, example: `/alternativeto/platform/firefox/license=free`

## Parameters
- `name`: Platform name
- `routeParams`: Filters of software type


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
  - `www.alternativeto.net/platform/:name`
- `target`: `/platform/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "> routeParms can be copied from original site URL, example: `/alternativeto/platform/firefox/license=free`",
  "example": "/alternativeto/platform/firefox",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "platform.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "Platform Software",
  "parameters": {
    "name": "Platform name",
    "routeParams": "Filters of software type"
  },
  "path": "/platform/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "www.alternativeto.net/platform/:name"
      ],
      "target": "/platform/:name"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
