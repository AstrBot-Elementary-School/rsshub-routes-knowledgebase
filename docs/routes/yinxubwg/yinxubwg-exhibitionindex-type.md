# Yinxu Museum - Exhibition Information

## Coverage
`index-only`

## Route
- Namespace: `yinxubwg`
- Namespace Name: `Yinxu Museum`
- Route Path: `/yinxubwg/exhibitionIndex/:type`
- Route Name: `Exhibition Information`
- Example: `/yinxubwg/exhibitionIndex/2`
- URL: `www.yinxubwg.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type. Supported values: `1` (Permanent Exhibition), `2` (Temporary Exhibition), `3` (Past Exhibitions).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.yinxubwg.cn/yxgw/exhibitionIndex`
- `target`: `/exhibitionIndex/:type`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/yinxubwg/exhibitionIndex/2",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibition Information",
  "parameters": {
    "type": "Exhibition type. Supported values: `1` (Permanent Exhibition), `2` (Temporary Exhibition), `3` (Past Exhibitions)."
  },
  "path": "/exhibitionIndex/:type",
  "radar": [
    {
      "source": [
        "www.yinxubwg.cn/yxgw/exhibitionIndex"
      ],
      "target": "/exhibitionIndex/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
