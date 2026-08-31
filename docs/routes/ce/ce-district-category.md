# 中国经济网 - 地方经济

## Coverage
`index-only`

## Route
- Namespace: `ce`
- Namespace Name: `中国经济网`
- Route Path: `/ce/district/:category?`
- Route Name: `地方经济`
- Example: `/ce/district`
- URL: `district.ce.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `cscnk52`
- Source Location: `district.ts`
- Source Module: `_None_`

## Description
| 即时新闻 | 经济动态 | 独家视角 | 专题 | 数说地方 | 地方播报 | 专稿 | 港澳台 |
| -------- | -------- | -------- | ---- | -------- | -------- | ---- | ------ |
| roll     | jjdt     | poll     | ch   | ssdf     | dfbb     | zg   | gat    |

## Parameters
- `category`: 栏目标识，默认为 roll（即时新闻）


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
  - `district.ce.cn/newarea/:category/index.shtml`
- `target`: `/district/:category?`
### Rule 2
- `source`:
  - `district.ce.cn/newarea/:category`
- `target`: `/district/:category?`
### Rule 3
- `source`:
  - `district.ce.cn`
- `target`: `/district`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即时新闻 | 经济动态 | 独家视角 | 专题 | 数说地方 | 地方播报 | 专稿 | 港澳台 |\n| -------- | -------- | -------- | ---- | -------- | -------- | ---- | ------ |\n| roll     | jjdt     | poll     | ch   | ssdf     | dfbb     | zg   | gat    |",
  "example": "/ce/district",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 15,
  "location": "district.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "地方经济",
  "parameters": {
    "category": "栏目标识，默认为 roll（即时新闻）"
  },
  "path": "/district/:category?",
  "radar": [
    {
      "source": [
        "district.ce.cn/newarea/:category/index.shtml"
      ],
      "target": "/district/:category?"
    },
    {
      "source": [
        "district.ce.cn/newarea/:category"
      ],
      "target": "/district/:category?"
    },
    {
      "source": [
        "district.ce.cn"
      ],
      "target": "/district"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国经济网地方经济 - 鍗虫椂鏂伴椈 - Powered by RSSHub",
      "errorAt": "2026-08-04T23:56:35.228Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "105835124893595648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://district.ce.cn/newarea/roll/index.shtml",
      "title": "中国经济网地方经济 - 鍗虫椂鏂伴椈",
      "type": "feed",
      "url": "rsshub://ce/district"
    }
  ],
  "url": "district.ce.cn",
  "view": 0
}
```
