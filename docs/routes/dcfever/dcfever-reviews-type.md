# DCFever - 測試報告

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/dcfever/reviews/:type?`
- Route Name: `測試報告`
- Example: `/dcfever/reviews/cameras`
- URL: `dcfever.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `reviews.ts`
- Source Module: `_None_`

## Description
| 相機及鏡頭 | 手機平板 | 試車報告 |
| ---------- | -------- | -------- |
| cameras    | phones   | cars     |

## Parameters
- `type`: 分類，預設為 `cameras`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dcfever.com/:type/reviews.php`
- `target`: `/reviews/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 相機及鏡頭 | 手機平板 | 試車報告 |\n| ---------- | -------- | -------- |\n| cameras    | phones   | cars     |",
  "example": "/dcfever/reviews/cameras",
  "heat": 30,
  "location": "reviews.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "測試報告",
  "parameters": {
    "type": "分類，預設為 `cameras`"
  },
  "path": "/reviews/:type?",
  "radar": [
    {
      "source": [
        "dcfever.com/:type/reviews.php"
      ],
      "target": "/reviews/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "相機及鏡頭測試報告 Camera and Lens Reviews - DCFever.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84292992343678976",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/cameras/reviews.php",
      "title": "相機及鏡頭測試報告 Camera and Lens Reviews - DCFever.com",
      "type": "feed",
      "url": "rsshub://dcfever/reviews"
    },
    {
      "description": "汽車電動車最新行情 Cars & Electric Cars Testing - DCFever.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63944676322037761",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/cars/reviews.php",
      "title": "汽車電動車最新行情 Cars & Electric Cars Testing - DCFever.com",
      "type": "feed",
      "url": "rsshub://dcfever/reviews/cars"
    }
  ]
}
```
