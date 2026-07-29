# 西南交通大学 - 就业招聘信息

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/jyzpxx`
- Route Name: `就业招聘信息`
- Example: `/swjtu/jyzpxx`
- URL: `jiuye.swjtu.edu.cn/career`
- Language: `_None_`
- Categories: `university`
- Maintainers: `qizidog`
- Source Location: `jyzpxx.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `jiuye.swjtu.edu.cn/career`
  - `jiuye.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/swjtu/jyzpxx",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "jyzpxx.ts",
  "maintainers": [
    "qizidog"
  ],
  "name": "就业招聘信息",
  "parameters": {},
  "path": "/jyzpxx",
  "radar": [
    {
      "source": [
        "jiuye.swjtu.edu.cn/career",
        "jiuye.swjtu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "西南交大-就业招聘信息 - Powered by RSSHub",
      "errorAt": "2025-10-29T10:50:03.841Z",
      "errorMessage": "[POST] \"https://jiuye.swjtu.edu.cn/career/zpxx/search/zpxx/1/10\": <no response> fetch failed\n",
      "id": "114200747238879232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jiuye.swjtu.edu.cn/career/zpxx/zpxx",
      "title": "西南交大-就业招聘信息",
      "type": "feed",
      "url": "rsshub://swjtu/jyzpxx"
    }
  ],
  "url": "jiuye.swjtu.edu.cn/career"
}
```
