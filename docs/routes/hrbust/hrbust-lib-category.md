# 哈尔滨理工大学 - 图书馆

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/lib/:category?`
- Route Name: `图书馆`
- Example: `/hrbust/lib`
- URL: `lib.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `lib.ts`
- Source Module: `_None_`

## Description
| 公告消息 | 资源动态 | 参考中心 | 常用工具 | 外借服务 | 报告厅及研讨间服务 | 外文引进数据库 | 外文电子图书 | 外文试用数据库 | 中文引进数据库 | 中文电子图书 | 中文试用数据库 |
| -------- | -------- | -------- | -------- | -------- | ------------------ | -------------- | ------------ | -------------- | -------------- | ------------ | -------------- |
| 3421     | 3422     | ckzx     | cygj     | wjfw     | ytjfw              | yw             | yw\_3392     | yw\_3395       | zw             | zw\_3391     | zw\_3394       |

## Parameters
- `category`: 栏目标识，默认为 3421（公告消息）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `lib.hrbust.edu.cn/:category/list.htm`
- `target`: `/lib/:category`
### Rule 2
- `source`:
  - `lib.hrbust.edu.cn`
- `target`: `/lib`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告消息 | 资源动态 | 参考中心 | 常用工具 | 外借服务 | 报告厅及研讨间服务 | 外文引进数据库 | 外文电子图书 | 外文试用数据库 | 中文引进数据库 | 中文电子图书 | 中文试用数据库 |\n| -------- | -------- | -------- | -------- | -------- | ------------------ | -------------- | ------------ | -------------- | -------------- | ------------ | -------------- |\n| 3421     | 3422     | ckzx     | cygj     | wjfw     | ytjfw              | yw             | yw\\_3392     | yw\\_3395       | zw             | zw\\_3391     | zw\\_3394       |",
  "example": "/hrbust/lib",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "lib.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "图书馆",
  "parameters": {
    "category": "栏目标识，默认为 3421（公告消息）"
  },
  "path": "/lib/:category?",
  "radar": [
    {
      "source": [
        "lib.hrbust.edu.cn/:category/list.htm"
      ],
      "target": "/lib/:category"
    },
    {
      "source": [
        "lib.hrbust.edu.cn"
      ],
      "target": "/lib"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "公告消息 - 哈尔滨理工大学图书馆 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114845629003558912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lib.hrbust.edu.cn/3421/list.htm",
      "title": "公告消息 - 哈尔滨理工大学图书馆",
      "type": "feed",
      "url": "rsshub://hrbust/lib"
    }
  ],
  "url": "lib.hrbust.edu.cn",
  "view": 5
}
```
