# 三立新聞網 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `setn`
- Namespace Name: `三立新聞網`
- Route Path: `/setn/:category?`
- Route Name: `新聞`
- Example: `/setn`
- URL: `setn.com/ViewAll.aspx`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 即時 | 熱門 | 娛樂 | 政治 | 社會 |
| ---- | ---- | ---- | ---- | ---- |

| 國際 | 兩岸 | 生活 | 健康 | 旅遊 |
| ---- | ---- | ---- | ---- | ---- |

| 運動 | 地方 | 財經 | 富房網 | 名家 |
| ---- | ---- | ---- | ------ | ---- |

| 新奇 | 科技 | 汽車 | 寵物 | 女孩 | HOT 焦點 |
| ---- | ---- | ---- | ---- | ---- | -------- |

## Parameters
- `category`: 分类，见下表，默认为即時


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
  - `setn.com/ViewAll.aspx`
  - `setn.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即時 | 熱門 | 娛樂 | 政治 | 社會 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 國際 | 兩岸 | 生活 | 健康 | 旅遊 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 運動 | 地方 | 財經 | 富房網 | 名家 |\n| ---- | ---- | ---- | ------ | ---- |\n\n| 新奇 | 科技 | 汽車 | 寵物 | 女孩 | HOT 焦點 |\n| ---- | ---- | ---- | ---- | ---- | -------- |",
  "example": "/setn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 127,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新聞",
  "parameters": {
    "category": "分类，见下表，默认为即時"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "setn.com/ViewAll.aspx",
        "setn.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "三立新聞網 - 即時 - Powered by RSSHub",
      "errorAt": "2026-07-05T15:13:53.172Z",
      "errorMessage": "502 \nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "55863308067829760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.setn.com/ViewAll.aspx",
      "title": "三立新聞網 - 即時",
      "type": "feed",
      "url": "rsshub://setn"
    },
    {
      "description": "三立新聞網 - 政治 - Powered by RSSHub",
      "errorAt": "2026-07-05T12:10:44.402Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "88520448616402944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.setn.com/ViewAll.aspx?PageGroupID=6",
      "title": "三立新聞網 - 政治",
      "type": "feed",
      "url": "rsshub://setn/%E6%94%BF%E6%B2%BB"
    }
  ],
  "url": "setn.com/ViewAll.aspx"
}
```
