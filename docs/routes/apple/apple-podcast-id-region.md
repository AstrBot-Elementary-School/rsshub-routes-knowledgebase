# Apple - 播客

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/apple/podcast/:id/:region?`
- Route Name: `播客`
- Example: `/apple/podcast/id1559695855/cn`
- URL: `www.apple.com/apple-podcasts/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Acring`
- Source Location: `podcast.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 播客id，可以在 Apple 播客app 内分享的播客的 URL 中找到
- `region`: 地區代碼，例如 cn、us、jp，預設為 cn


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
  - `podcasts.apple.com/:region/podcast/:showName/:id`
  - `podcasts.apple.com/:region/podcast/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/apple/podcast/id1559695855/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 319,
  "location": "podcast.ts",
  "maintainers": [
    "Acring"
  ],
  "name": "播客",
  "parameters": {
    "id": "播客id，可以在 Apple 播客app 内分享的播客的 URL 中找到",
    "region": "地區代碼，例如 cn、us、jp，預設為 cn"
  },
  "path": "/podcast/:id/:region?",
  "radar": [
    {
      "source": [
        "podcasts.apple.com/:region/podcast/:showName/:id",
        "podcasts.apple.com/:region/podcast/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《知行小酒馆》是有知有行出品的一档分享投资与生活的播客节目。我们关注投资理财，更关注怎样更好地生活。在我们看来，投资成功，是我们变成一个更好的人之后，自然的结果。 如果你对节目有任何建议，或者有推荐的嘉宾，或者只是想与我们分享你和小酒馆的故事，可以给我们发邮件，来信请寄：allinthebeer@gmail.com 如果你有长期投资的需求，非常欢迎下载 有知有行App，里面有你一定能读懂的好课程《投资第一课》，也有专业的投资观察《知行黑板报》，更有我们全员持有的好产品「长钱账户」「稳钱账户」「海外长钱」，人称「长稳海三胞胎」。 - Powered by RSSHub",
      "errorAt": "2026-06-16T17:46:33.167Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "67618686621496320",
      "image": "https://is1-ssl.mzstatic.com/image/thumb/PodcastSource221/v4/ee/7a/b0/ee7ab0cb-6edd-fcb5-f249-601a80ab3f74/40ada4a7-0066-4934-8ccc-a4b25e69a029.png/3000x3000bb.webp",
      "ownerUserId": null,
      "siteUrl": "https://podcasts.apple.com/us/channel/%E6%9C%89%E7%9F%A5%E6%9C%89%E8%A1%8C/id6737803099",
      "title": "有知有行",
      "type": "feed",
      "url": "rsshub://apple/podcast/id1559695855"
    },
    {
      "description": "一个十五分钟的晨间仪式，轻松同步日常生活与商业世界。 这是一档由声动活泼出品的清晨播客节目，在工作日的早晨，为你带来与日常生活息息相关的商业科技轻解读，开启能量满满新一天。 - Powered by RSSHub",
      "errorAt": "2026-06-17T06:20:21.209Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "75431705723333633",
      "image": "https://is1-ssl.mzstatic.com/image/thumb/PodcastSource116/v4/ed/f3/4c/edf34c1e-6986-b477-9844-44c83ed8a43e/67f4f01b-132f-4111-8f8f-743dcbada911.png/3000x3000bb.webp",
      "ownerUserId": null,
      "siteUrl": "https://podcasts.apple.com/us/channel/%E5%A3%B0%E5%8A%A8%E6%B4%BB%E6%B3%BC/id6442523325",
      "title": "声动活泼",
      "type": "feed",
      "url": "rsshub://apple/podcast/id1573189055"
    }
  ],
  "url": "www.apple.com/apple-podcasts/"
}
```
