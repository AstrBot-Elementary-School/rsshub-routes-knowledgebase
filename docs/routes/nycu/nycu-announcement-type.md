# National Yang Ming Chiao Tung University - 校園公告

## Coverage
`index-only`

## Route
- Namespace: `nycu`
- Namespace Name: `National Yang Ming Chiao Tung University`
- Route Path: `/nycu/announcement/:type`
- Route Name: `校園公告`
- Example: `/nycu/announcement/5`
- URL: `nycu.edu.tw`
- Language: `_None_`
- Categories: `university`
- Maintainers: `simbafs`
- Source Location: `announcement.ts`
- Source Module: `_None_`

## Description
|   名稱   | :type |
| :------: | :---: |
| 行政公告 |   5   |
| 演講課程 |   6   |
| 藝文體育 |   7   |
| 校園徵才 |   9   |
| 其他活動 |   8   |
| 電子公文 |   3   |
| 校外訊息 |   10  |

## Parameters
- `type`: 類型，見下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "|   名稱   | :type |\n| :------: | :---: |\n| 行政公告 |   5   |\n| 演講課程 |   6   |\n| 藝文體育 |   7   |\n| 校園徵才 |   9   |\n| 其他活動 |   8   |\n| 電子公文 |   3   |\n| 校外訊息 |   10  |",
  "example": "/nycu/announcement/5",
  "heat": 0,
  "location": "announcement.ts",
  "maintainers": [
    "simbafs"
  ],
  "name": "校園公告",
  "parameters": {
    "type": "類型，見下表"
  },
  "path": "/announcement/:type",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
