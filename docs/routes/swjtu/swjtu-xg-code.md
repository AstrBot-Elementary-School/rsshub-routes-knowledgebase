# 西南交通大学 - 扬华素质网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/xg/:code?`
- Route Name: `扬华素质网`
- Example: `/swjtu/xg/tzgg`
- URL: `xg.swjtu.edu.cn/web/Home/PushNewsList`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `xg.ts`
- Source Module: `_None_`

## Description
栏目列表：

| 通知公告 | 扬华新闻 | 多彩学院 | 学工之家 |
| -------- | -------- | -------- | -------- |
| tzgg     | yhxw     | dcxy     | xgzj     |

## Parameters
- `code`: 栏目(默认为tzgg)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xg.swjtu.edu.cn/web/Home/PushNewsList`
  - `xg.swjtu.edu.cn/web/Home/NewsList`
  - `xg.swjtu.edu.cn/web/Home/ColourfulCollegeNewsList`
  - `xg.swjtu.edu.cn/web/Publicity/List`
  - `xg.swjtu.edu.cn/`
- `target`: `/xg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目列表：\n\n| 通知公告 | 扬华新闻 | 多彩学院 | 学工之家 |\n| -------- | -------- | -------- | -------- |\n| tzgg     | yhxw     | dcxy     | xgzj     |",
  "example": "/swjtu/xg/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "xg.ts",
  "maintainers": [
    "mobyw"
  ],
  "name": "扬华素质网",
  "parameters": {
    "code": "栏目(默认为tzgg)"
  },
  "path": "/xg/:code?",
  "radar": [
    {
      "source": [
        "xg.swjtu.edu.cn/web/Home/PushNewsList",
        "xg.swjtu.edu.cn/web/Home/NewsList",
        "xg.swjtu.edu.cn/web/Home/ColourfulCollegeNewsList",
        "xg.swjtu.edu.cn/web/Publicity/List",
        "xg.swjtu.edu.cn/"
      ],
      "target": "/xg"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "西南交大-扬华素质网 - Powered by RSSHub",
      "errorAt": "2026-07-24T01:36:37.543Z",
      "errorMessage": "[GET] \"http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 180.85.38.124:80, 2001:da8:6005:6:b455:267c:::80, timeout: 10000ms))\n",
      "id": "72512219481102338",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml",
      "title": "西南交大-扬华素质网",
      "type": "feed",
      "url": "rsshub://swjtu/xg/tzgg"
    },
    {
      "description": "西南交大-扬华素质网 - Powered by RSSHub",
      "errorAt": "2025-10-29T11:20:45.197Z",
      "errorMessage": "[GET] \"http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml\": <no response> fetch failed\n",
      "id": "206259218544363520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml",
      "title": "西南交大-扬华素质网",
      "type": "feed",
      "url": "rsshub://swjtu/xg"
    }
  ],
  "url": "xg.swjtu.edu.cn/web/Home/PushNewsList"
}
```
