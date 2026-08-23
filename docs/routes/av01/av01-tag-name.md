# AV01 - 分类

## Coverage
`index-only`

## Route
- Namespace: `av01`
- Namespace Name: `AV01`
- Route Path: `/av01/tag/:name`
- Route Name: `分类`
- Example: `/av01/tag/中出し`
- URL: `www.av01.media`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `CorrectRoadH`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 分类名或 id，仅限日语，可直接在网站上找到


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.av01.media/:language/tag/:name/:unusedName`
  - `www.av01.media/:language/tag/:name`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/av01/tag/中出し",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "CorrectRoadH"
  ],
  "name": "分类",
  "parameters": {
    "name": "分类名或 id，仅限日语，可直接在网站上找到"
  },
  "path": "/tag/:name",
  "radar": [
    {
      "source": [
        "www.av01.media/:language/tag/:name/:unusedName",
        "www.av01.media/:language/tag/:name"
      ]
    }
  ],
  "topFeeds": []
}
```
