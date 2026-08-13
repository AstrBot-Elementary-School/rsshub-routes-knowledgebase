# 四川农业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/sicau/jiaowu/jxtz/:detail?`
- Route Name: `教务处`
- Example: `/sicau/jiaowu/jxtz/detail`
- URL: `jiaowu.sicau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hualiong`
- Source Location: `jiaowu.ts`
- Source Module: `_None_`

## Description
::: tip
抓取全文返回会导致更长的响应时间，可以尝试使用 `/sicau/jiaowu/jxtz` 路径，这将只返回标题，然后再在应用内抓取全文内容。
:::

## Parameters
- `detail`: 是否抓取全文，该值只要不为空就抓取全文返回，否则只返回标题


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
  - `jiaowu.sicau.edu.cn/web/web/web/index.asp`
- `target`: `/jiaowu/jxtz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n抓取全文返回会导致更长的响应时间，可以尝试使用 `/sicau/jiaowu/jxtz` 路径，这将只返回标题，然后再在应用内抓取全文内容。\n:::",
  "example": "/sicau/jiaowu/jxtz/detail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "jiaowu.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "教务处",
  "parameters": {
    "detail": "是否抓取全文，该值只要不为空就抓取全文返回，否则只返回标题"
  },
  "path": "/jiaowu/jxtz/:detail?",
  "radar": [
    {
      "source": [
        "jiaowu.sicau.edu.cn/web/web/web/index.asp"
      ],
      "target": "/jiaowu/jxtz"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "教学通知 - 四川农业大学教务处 - Powered by RSSHub",
      "errorAt": "2025-10-19T01:59:29.617Z",
      "errorMessage": "[GET] \"https://jiaowu.sicau.edu.cn/web/web/web/gwmore.asp\": <no response> fetch failed\n",
      "id": "169257483441609728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jiaowu.sicau.edu.cn/web/web/web/gwmore.asp",
      "title": "教学通知 - 四川农业大学教务处",
      "type": "feed",
      "url": "rsshub://sicau/jiaowu/jxtz/detail"
    },
    {
      "description": "教学通知 - 四川农业大学教务处 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114192527916693504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jiaowu.sicau.edu.cn/web/web/web/gwmore.asp",
      "title": "教学通知 - 四川农业大学教务处",
      "type": "feed",
      "url": "rsshub://sicau/jiaowu/jxtz"
    }
  ],
  "url": "jiaowu.sicau.edu.cn/"
}
```
