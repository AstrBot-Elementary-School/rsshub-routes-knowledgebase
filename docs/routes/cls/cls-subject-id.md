# 财联社 - 话题

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/cls/subject/:id?`
- Route Name: `话题`
- Example: `/cls/subject/1103`
- URL: `www.cls.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `subject.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [有声早报](https://www.cls.cn/subject/1151)，网址为 `https://www.cls.cn/subject/1151`。截取 `https://www.cls.cn/subject/` 到末尾的部分 `1151` 作为参数填入，此时路由为 [`/cls/subject/1151`](https://rsshub.app/cls/subject/1151)。
:::

## Parameters
- `category`: 分类，默认为 1103，即A股盘面直播，可在对应话题页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.cls.cn/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [有声早报](https://www.cls.cn/subject/1151)，网址为 `https://www.cls.cn/subject/1151`。截取 `https://www.cls.cn/subject/` 到末尾的部分 `1151` 作为参数填入，此时路由为 [`/cls/subject/1151`](https://rsshub.app/cls/subject/1151)。\n:::",
  "example": "/cls/subject/1103",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 150,
  "location": "subject.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "话题",
  "parameters": {
    "category": "分类，默认为 1103，即A股盘面直播，可在对应话题页 URL 中找到"
  },
  "path": "/subject/:id?",
  "radar": [
    {
      "source": [
        "www.cls.cn/subject/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "汽车行业资讯一网打尽。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102251632021746688",
      "image": "https://img.cls.cn/images/20211116/r2NZ9gCUzN.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/subject/7527",
      "title": "财联社 - 财联社汽车早报",
      "type": "feed",
      "url": "rsshub://cls/subject/7527"
    },
    {
      "description": "财联社 - 有声早报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69656992151508992",
      "image": "https://img.cls.cn/images/20230626/VTro88PCM7.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/subject/1151",
      "title": "财联社 - 有声早报",
      "type": "feed",
      "url": "rsshub://cls/subject/1151"
    }
  ],
  "url": "www.cls.cn"
}
```
