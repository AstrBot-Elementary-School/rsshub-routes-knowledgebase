# 晚点 LatePost - 报道

## Coverage
`index-only`

## Route
- Namespace: `latepost`
- Namespace Name: `晚点 LatePost`
- Route Path: `/latepost/:proma?`
- Route Name: `报道`
- Example: `/latepost`
- URL: `latepost.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新报道 | 晚点独家 | 人物访谈 | 晚点早知道 | 长报道 |
| -------- | -------- | -------- | ---------- | ------ |
|          | 1        | 2        | 3          | 4      |

## Parameters
- `proma`: 栏目 id，见下表，默认为最新报道


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "| 最新报道 | 晚点独家 | 人物访谈 | 晚点早知道 | 长报道 |\n| -------- | -------- | -------- | ---------- | ------ |\n|          | 1        | 2        | 3          | 4      |",
  "example": "/latepost",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7212,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "报道",
  "parameters": {
    "proma": "栏目 id，见下表，默认为最新报道"
  },
  "path": "/:proma?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "晚一点，好一点 Later better - Powered by RSSHub",
      "errorAt": "2026-07-27T13:41:13.147Z",
      "errorMessage": "[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\nAuthentication failed. Access denied.\n/latepost/4\n502 \n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (certificate has expired)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n",
      "id": "57976037240744981",
      "image": "https://www.latepost.com/images/logo_txt_header.png",
      "ownerUserId": null,
      "siteUrl": "https://www.latepost.com/news/index?proma=4",
      "title": "晚点 - 长报道",
      "type": "feed",
      "url": "rsshub://latepost/4"
    },
    {
      "description": "晚一点，好一点 Later better - Powered by RSSHub",
      "errorAt": "2026-07-26T21:42:10.437Z",
      "errorMessage": "[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\nAuthentication failed. Access denied.\n/latepost\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (certificate has expired)\n502 \n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed\nFailed to fetch\n[GET] \"https://www.latepost.com/site/get-column\": <no response> fetch failed (unable to get local issuer certificate)\n",
      "id": "42176727619514397",
      "image": "https://www.latepost.com/images/logo_txt_header.png",
      "ownerUserId": null,
      "siteUrl": "https://www.latepost.com/",
      "title": "晚点 - 最新报道",
      "type": "feed",
      "url": "rsshub://latepost"
    }
  ]
}
```
