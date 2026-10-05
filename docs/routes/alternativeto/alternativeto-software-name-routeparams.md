# AlternativeTo - Software Alternatives

## Coverage
`index-only`

## Route
- Namespace: `alternativeto`
- Namespace Name: `AlternativeTo`
- Route Path: `/alternativeto/software/:name/:routeParams?`
- Route Name: `Software Alternatives`
- Example: `/alternativeto/software/cpp`
- URL: `www.alternativeto.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JimenezLi`
- Source Location: `software.ts`
- Source Module: `_None_`

## Description
> routeParms can be copied from original site URL, example: `/alternativeto/software/cpp/license=opensource&platform=windows`

## Parameters
- `name`: Software name
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
  - `www.alternativeto.net/software/:name`
- `target`: `/software/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "> routeParms can be copied from original site URL, example: `/alternativeto/software/cpp/license=opensource&platform=windows`",
  "example": "/alternativeto/software/cpp",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "software.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "Software Alternatives",
  "parameters": {
    "name": "Software name",
    "routeParams": "Filters of software type"
  },
  "path": "/software/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "www.alternativeto.net/software/:name"
      ],
      "target": "/software/:name"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
