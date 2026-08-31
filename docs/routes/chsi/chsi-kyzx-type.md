# 中国研究生招生信息网 - 考研资讯

## Coverage
`index-only`

## Route
- Namespace: `chsi`
- Namespace Name: `中国研究生招生信息网`
- Route Path: `/chsi/kyzx/:type`
- Route Name: `考研资讯`
- Example: `/chsi/kyzx/fstj`
- URL: `yz.chsi.com.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `yanbot-team`
- Source Location: `kyzx.ts`
- Source Module: `_None_`

## Description
| `:type` | 专题名称 |
| ------- | -------- |
| fstj    | 复试调剂 |
| kydt    | 考研动态 |
| zcdh    | 政策导航 |
| kyrw    | 考研人物 |
| jyxd    | 经验心得 |

## Parameters
- `type`: type 见下表，亦可在网站 URL 找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yz.chsi.com.cn/kyzx/:type`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:type` | 专题名称 |\n| ------- | -------- |\n| fstj    | 复试调剂 |\n| kydt    | 考研动态 |\n| zcdh    | 政策导航 |\n| kyrw    | 考研人物 |\n| jyxd    | 经验心得 |",
  "example": "/chsi/kyzx/fstj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "kyzx.ts",
  "maintainers": [
    "yanbot-team"
  ],
  "name": "考研资讯",
  "parameters": {
    "type": " type 见下表，亦可在网站 URL 找到"
  },
  "path": "/kyzx/:type",
  "radar": [
    {
      "source": [
        "yz.chsi.com.cn/kyzx/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国研究生招生信息网 - 考研资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74787247590792206",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yz.chsi.com.cn/kyzx/fstj/",
      "title": "中国研究生招生信息网 - 考研资讯",
      "type": "feed",
      "url": "rsshub://chsi/kyzx/fstj"
    },
    {
      "description": "中国研究生招生信息网 - 考研资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65029213581827072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yz.chsi.com.cn/kyzx/jyxd/",
      "title": "中国研究生招生信息网 - 考研资讯",
      "type": "feed",
      "url": "rsshub://chsi/kyzx/jyxd"
    }
  ]
}
```
