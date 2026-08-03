# 理想生活实验室 - 领域

## Coverage
`index-only`

## Route
- Namespace: `toodaylab`
- Namespace Name: `理想生活实验室`
- Route Path: `/toodaylab/field/:id`
- Route Name: `领域`
- Example: `/toodaylab/field/308`
- URL: `toodaylab.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `field.ts`
- Source Module: `_None_`

## Description
| 快消 | 时尚 | 智能 | 娱乐 | 运动 | 生活 | 设计 | 出行 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 308  | 307  | 306  | 305  | 304  | 303  | 302  | 301  |

## Parameters
- `id`: 领域 id，见下表，可在对应领域页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `toodaylab.com/field/:id`
- `target`: `/field/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 快消 | 时尚 | 智能 | 娱乐 | 运动 | 生活 | 设计 | 出行 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 308  | 307  | 306  | 305  | 304  | 303  | 302  | 301  |",
  "example": "/toodaylab/field/308",
  "heat": 0,
  "location": "field.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "领域",
  "parameters": {
    "id": "领域 id，见下表，可在对应领域页 URL 中找到"
  },
  "path": "/field/:id",
  "radar": [
    {
      "source": [
        "toodaylab.com/field/:id"
      ],
      "target": "/field/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
