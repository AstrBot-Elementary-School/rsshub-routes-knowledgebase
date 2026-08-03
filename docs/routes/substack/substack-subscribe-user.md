# Substack - Substack Subscription

## Coverage
`index-only`

## Route
- Namespace: `substack`
- Namespace Name: `Substack`
- Route Path: `/substack/subscribe/:user`
- Route Name: `Substack Subscription`
- Example: `/substack/subscribe/mangoread`
- URL: `substack.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `pseudoyu`
- Source Location: `subscribe.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Username of the Substack


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
    "blog"
  ],
  "example": "/substack/subscribe/mangoread",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 277,
  "location": "subscribe.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Substack Subscription",
  "parameters": {
    "user": "Username of the Substack"
  },
  "path": "/subscribe/:user",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "世界苦茶龐大體系下1500字（感覺不只）左右的文章，都是關於政治學和政治哲學的思考 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "176031166219999232",
      "image": "https://substackcdn.com/image/fetch/$s_!ulvf!,w_256,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F06156f61-eead-4e42-a104-6f2193a7b8d1_4000x4000.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://bittertea.substack.com/",
      "title": "世界苦茶「The Political Condition」",
      "type": "feed",
      "url": "rsshub://substack/subscribe/bittertea"
    },
    {
      "description": "水瓶纪元 | The Aquarian 多元共生 · 重返对话 Journalism for Futures - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "132968001832526848",
      "image": "https://substackcdn.com/image/fetch/$s_!5vrA!,w_256,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F76978654-f1e4-4e4f-960f-9c798035f650_157x157.png",
      "ownerUserId": null,
      "siteUrl": "https://aquarianhq.substack.com/",
      "title": "水瓶纪元",
      "type": "feed",
      "url": "rsshub://substack/subscribe/aquariuseras"
    }
  ],
  "view": 1
}
```
