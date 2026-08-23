# AV01 - 演员

## Coverage
`index-only`

## Route
- Namespace: `av01`
- Namespace Name: `AV01`
- Route Path: `/av01/actor/:name`
- Route Name: `演员`
- Example: `/av01/actor/七沢みあ`
- URL: `www.av01.media`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `CorrectRoadH`
- Source Location: `actor.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 女优名或 id，仅限日语，可直接在网站上找到


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.av01.media/:language/actress/:name/:unusedName`
  - `www.av01.media/:language/actress/:name`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/av01/actor/七沢みあ",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "actor.ts",
  "maintainers": [
    "CorrectRoadH"
  ],
  "name": "演员",
  "parameters": {
    "name": "女优名或 id，仅限日语，可直接在网站上找到"
  },
  "path": "/actor/:name",
  "radar": [
    {
      "source": [
        "www.av01.media/:language/actress/:name/:unusedName",
        "www.av01.media/:language/actress/:name"
      ]
    }
  ],
  "topFeeds": []
}
```
