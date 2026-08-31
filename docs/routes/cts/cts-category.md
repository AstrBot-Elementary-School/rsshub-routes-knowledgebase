# 華視 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `cts`
- Namespace Name: `華視`
- Route Path: `/cts/:category`
- Route Name: `新聞`
- Example: `/cts/real`
- URL: `news.cts.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `miles170`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 即時 | 氣象    | 政治     | 國際          | 社會    | 運動   | 生活 | 財經  | 台語      | 地方  | 產業 | 綜合    | 藝文 | 娛樂      |
| ---- | ------- | -------- | ------------- | ------- | ------ | ---- | ----- | --------- | ----- | ---- | ------- | ---- | --------- |
| real | weather | politics | international | society | sports | life | money | taiwanese | local | pr   | general | arts | entertain |

## Parameters
- `category`: 类别


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
  - `news.cts.com.tw/:category/index.html`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即時 | 氣象    | 政治     | 國際          | 社會    | 運動   | 生活 | 財經  | 台語      | 地方  | 產業 | 綜合    | 藝文 | 娛樂      |\n| ---- | ------- | -------- | ------------- | ------- | ------ | ---- | ----- | --------- | ----- | ---- | ------- | ---- | --------- |\n| real | weather | politics | international | society | sports | life | money | taiwanese | local | pr   | general | arts | entertain |",
  "example": "/cts/real",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "新聞",
  "parameters": {
    "category": "类别"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "news.cts.com.tw/:category/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "華視 提供最新新聞,戲劇,綜藝,卡通,教學,綜合,影音,節目表等資訊。電話：(02)2775-6789 免付費服務專線: 0800-069-789 - Powered by RSSHub",
      "errorAt": "2026-04-14T06:27:58.682Z",
      "errorMessage": "[GET] \"https://news.cts.com.tw/real/index.html\": 410 \n[GET] \"https://news.cts.com.tw/real/index.html\": 410 Gone\n",
      "id": "152042616140212224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.cts.com.tw/real/index.html",
      "title": "華視新聞網 - 即時",
      "type": "feed",
      "url": "rsshub://cts/real"
    }
  ]
}
```
