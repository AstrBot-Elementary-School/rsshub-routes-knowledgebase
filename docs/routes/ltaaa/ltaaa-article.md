# 龙腾网 - 网站翻译

## Coverage
`index-only`

## Route
- Namespace: `ltaaa`
- Namespace Name: `龙腾网`
- Route Path: `/ltaaa/article`
- Route Name: `网站翻译`
- Example: `/ltaaa/article`
- URL: `www.ltaaa.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.ltaaa.cn/article`
- `target`: `/article`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ltaaa/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 13,
  "location": "article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "网站翻译",
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ltaaa.cn/article"
      ],
      "target": "/article"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "网贴翻译包括趣闻轶事,英语翻译,日语翻译,韩语翻译,德语翻译,西语翻译,法语翻译,翻译网 - Powered by RSSHub",
      "errorAt": "2026-07-19T17:39:58.669Z",
      "errorMessage": "[GET] \"https://www.ltaaa.cn/article\": <no response> fetch failed (Connect Timeout Error (attempted address: www.ltaaa.cn:443, timeout: 10000ms))\n",
      "id": "124430765697571840",
      "image": "https://www.ltaaa.cn/static/home/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ltaaa.cn/article",
      "title": "网贴翻译 - 龙腾网",
      "type": "feed",
      "url": "rsshub://ltaaa/article"
    }
  ],
  "url": "www.ltaaa.cn",
  "view": 0
}
```
