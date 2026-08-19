# Matters - Latest, heat, essence

## Coverage
`index-only`

## Route
- Namespace: `matters`
- Namespace Name: `Matters`
- Route Path: `/matters/latest/:type?`
- Route Name: `Latest, heat, essence`
- Example: `/matters/latest/heat`
- URL: `matters.town`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `xyqfer, Cerebrater, xosdy`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
| 最新   | 热门 | 精华    |
| ------ | ---- | ------- |
| latest | heat | essence |

## Parameters
- `uid`: Defaults to latest, see table below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `matters.town`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新   | 热门 | 精华    |\n| ------ | ---- | ------- |\n| latest | heat | essence |",
  "example": "/matters/latest/heat",
  "heat": 144,
  "location": "latest.ts",
  "maintainers": [
    "xyqfer",
    "Cerebrater",
    "xosdy"
  ],
  "name": "Latest, heat, essence",
  "parameters": {
    "uid": "Defaults to latest, see table below"
  },
  "path": "/latest/:type?",
  "radar": [
    {
      "source": [
        "matters.town"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Matters | 熱議 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905692",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://matters.town/",
      "title": "Matters | 熱議",
      "type": "feed",
      "url": "rsshub://matters/latest/heat"
    },
    {
      "description": "Matters | 精華 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905691",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://matters.town/",
      "title": "Matters | 精華",
      "type": "feed",
      "url": "rsshub://matters/latest/essence"
    }
  ]
}
```
