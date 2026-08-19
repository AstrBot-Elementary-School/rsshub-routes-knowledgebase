# 北京智源人工智能研究院 - 智源社区

## Coverage
`index-only`

## Route
- Namespace: `baai`
- Namespace Name: `北京智源人工智能研究院`
- Route Path: `/baai/hub/:tagId?/:sort?/:range?`
- Route Name: `智源社区`
- Example: `/baai/hub`
- URL: `hub.baai.ac.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `hub.ts`
- Source Module: `_None_`

## Description
排序

| 最新 | 最热    |
| ---- | ------- |
| new  | readCnt |

时间跨度

| 3 天 | 本周 | 本月 |
| ---- | ---- | ---- |
| 3    | 7    | 30   |

## Parameters
- `tagId`: 社群 ID，可在 [社群页](https://hub.baai.ac.cn/taglist) 或 URL 中找到
- `sort`: 排序，见下表，默认为 `new`
- `range`: 时间跨度，仅在排序 `readCnt` 时有效


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `baai.ac.cn/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "排序\n\n| 最新 | 最热    |\n| ---- | ------- |\n| new  | readCnt |\n\n时间跨度\n\n| 3 天 | 本周 | 本月 |\n| ---- | ---- | ---- |\n| 3    | 7    | 30   |",
  "example": "/baai/hub",
  "heat": 202,
  "location": "hub.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "智源社区",
  "parameters": {
    "range": "时间跨度，仅在排序 `readCnt` 时有效",
    "sort": "排序，见下表，默认为 `new`",
    "tagId": "社群 ID，可在 [社群页](https://hub.baai.ac.cn/taglist) 或 URL 中找到"
  },
  "path": "/hub/:tagId?/:sort?/:range?",
  "radar": [
    {
      "source": [
        "baai.ac.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "智源社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60522682885703680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.baai.ac.cn/?sort=new",
      "title": "智源社区",
      "type": "feed",
      "url": "rsshub://baai/hub"
    }
  ]
}
```
