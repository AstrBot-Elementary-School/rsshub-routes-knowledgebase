# 理想生活实验室 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `toodaylab`
- Namespace Name: `理想生活实验室`
- Route Path: `/toodaylab/column/:id`
- Route Name: `专栏`
- Example: `/toodaylab/column/299`
- URL: `toodaylab.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
| 专题 | 攻略 |
| ---- | ---- |
| 299  | 300  |

## Parameters
- `id`: 专栏 id，见下表，可在对应专栏页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `toodaylab.com/column/:id`
- `target`: `/column/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 专题 | 攻略 |\n| ---- | ---- |\n| 299  | 300  |",
  "example": "/toodaylab/column/299",
  "heat": 0,
  "location": "column.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，见下表，可在对应专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "toodaylab.com/column/:id"
      ],
      "target": "/column/:id"
    }
  ],
  "topFeeds": []
}
```
