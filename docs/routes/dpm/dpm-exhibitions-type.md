# The Palace Museum - Current Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `dpm`
- Namespace Name: `The Palace Museum`
- Route Path: `/dpm/exhibitions/:type?`
- Route Name: `Current Exhibitions`
- Example: `/dpm/exhibitions/temporary_exhibitions`
- URL: `www.dpm.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibitions.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: temporary_exhibitions（特展）、galleries（专馆）、longterm_exhibitions（常设展览）、period_halls（原状陈列）. Default: Current Exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dpm.org.cn/classify/exhibition.html`
- `target`: `/exhibitions`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/dpm/exhibitions/temporary_exhibitions",
  "heat": 1,
  "location": "exhibitions.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Current Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: temporary_exhibitions（特展）、galleries（专馆）、longterm_exhibitions（常设展览）、period_halls（原状陈列）. Default: Current Exhibitions."
  },
  "path": "/exhibitions/:type?",
  "radar": [
    {
      "source": [
        "www.dpm.org.cn/classify/exhibition.html"
      ],
      "target": "/exhibitions"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "故宫博物院 - 特展 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1268365424953524224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dpm.org.cn/classify/exhibition.html",
      "title": "故宫博物院 - 特展",
      "type": "feed",
      "url": "rsshub://dpm/exhibitions/temporary_exhibitions"
    }
  ]
}
```
