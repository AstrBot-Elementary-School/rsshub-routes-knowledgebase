# eTOLAND - 主题贴

## Coverage
`index-only`

## Route
- Namespace: `etoland`
- Namespace Name: `eTOLAND`
- Route Path: `/etoland/:bo_table`
- Route Name: `主题贴`
- Example: `/etoland/star01`
- URL: `etoland.co.kr`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `mengx8`
- Source Location: `board.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bo_table`: 板块 id，可在板块 URL 找到


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `etoland.co.kr/b/:bo_table/list`
- `target`: `/:bo_table`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/etoland/star01",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "board.ts",
  "maintainers": [
    "mengx8"
  ],
  "name": "主题贴",
  "parameters": {
    "bo_table": "板块 id，可在板块 URL 找到"
  },
  "path": "/:bo_table",
  "radar": [
    {
      "source": [
        "etoland.co.kr/b/:bo_table/list"
      ],
      "target": "/:bo_table"
    }
  ],
  "topFeeds": []
}
```
