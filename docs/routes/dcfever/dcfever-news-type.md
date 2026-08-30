# DCFever - 新聞中心

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/dcfever/news/:type?`
- Route Name: `新聞中心`
- Example: `/dcfever/news`
- URL: `dcfever.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 所有新聞 | 攝影器材 | 手機通訊 | 汽車熱話 | 攝影文化    | 影片攝錄    | 測試報告 | 生活科技 | 攝影技巧  |
| -------- | -------- | -------- | -------- | ----------- | ----------- | -------- | -------- | --------- |
|          | camera   | mobile   | auto     | photography | videography | reviews  | gadget   | technique |

## Parameters
- `type`: 分類，預設為所有新聞


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dcfever.com/news/index.php`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 所有新聞 | 攝影器材 | 手機通訊 | 汽車熱話 | 攝影文化    | 影片攝錄    | 測試報告 | 生活科技 | 攝影技巧  |\n| -------- | -------- | -------- | -------- | ----------- | ----------- | -------- | -------- | --------- |\n|          | camera   | mobile   | auto     | photography | videography | reviews  | gadget   | technique |",
  "example": "/dcfever/news",
  "heat": 155,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞中心",
  "parameters": {
    "type": "分類，預設為所有新聞"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "dcfever.com/news/index.php"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新消息 - DCFever.com 香港最受歡迎數碼產品資訊互動平台 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67022535379083293",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/news/index.php?type=undefined",
      "title": "最新消息 - DCFever.com 香港最受歡迎數碼產品資訊互動平台",
      "type": "feed",
      "url": "rsshub://dcfever/news"
    },
    {
      "description": "攝影器材 - DCFever.com 香港最受歡迎數碼產品資訊互動平台 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130186322692247552",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/news/index.php?type=camera",
      "title": "攝影器材 - DCFever.com 香港最受歡迎數碼產品資訊互動平台",
      "type": "feed",
      "url": "rsshub://dcfever/news/camera"
    }
  ]
}
```
