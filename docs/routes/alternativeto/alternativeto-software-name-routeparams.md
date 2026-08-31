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
- `requirePuppeteer`: true
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
    "requirePuppeteer": true,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
