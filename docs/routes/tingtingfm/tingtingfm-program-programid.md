# 听听 FM - 节目

## Coverage
`index-only`

## Route
- Namespace: `tingtingfm`
- Namespace Name: `听听 FM`
- Route Path: `/tingtingfm/program/:programId`
- Route Name: `节目`
- Example: `/tingtingfm/program/M7VJv6Jj4R`
- URL: `mobile.tingtingfm.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `program.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `programId`: 节目 ID，可以在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mobile.tingtingfm.com/v3/program/:programId`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/tingtingfm/program/M7VJv6Jj4R",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 121,
  "location": "program.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "节目",
  "parameters": {
    "programId": "节目 ID，可以在 URL 中找到"
  },
  "path": "/program/:programId",
  "radar": [
    {
      "source": [
        "mobile.tingtingfm.com/v3/program/:programId"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "《中国歌曲排行榜》是北京音乐广播1993年创建的内地历史最长、业界及听众心中最具权威度和公信力的华语流行音乐排行榜；多年来耕耘、扶持原创乐坛，推出海内外众多脍炙人口歌曲和著名歌手。囊括中国内地港台等地区时下最流行的中文歌曲TOP40四十首歌曲大排行，通过每周推出的中国原创流行歌曲，繁荣中国流行音乐创作，满足听众对于中文流行歌曲的趋势把控和欣赏的需求。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78983559888666624",
      "image": "https://ttfm2018pub-oss-cdn.tingtingfm.com/cover/2021/0823/91/35/91357c17d4997d77e838ad95045036b0.jpg",
      "ownerUserId": null,
      "siteUrl": "https://mobile.tingtingfm.com/v3/program/q0boxOndrg",
      "title": "中国歌曲排行榜 - 北京音乐广播FM97.4",
      "type": "feed",
      "url": "rsshub://tingtingfm/program/q0boxOndrg"
    },
    {
      "description": "《1039新闻早报》是交通广播全力打造的一档早间新闻直播节目，节目的口号是“用新鲜资讯叫醒北京城”。节目秉承时效性、本地性、服务性的方针，力求通过自然轻松的播报方式，为听众献上一道丰盛的早间新闻大餐。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73904811865636864",
      "image": "https://ttfm2018pub-oss-cdn.tingtingfm.com/cover/2021/1223/14/6d/146da2f9ecf3daf4d6734f7b6d37113c.jpg",
      "ownerUserId": null,
      "siteUrl": "https://mobile.tingtingfm.com/v3/program/EOAonLJy7G",
      "title": "1039新闻早报 - 北京交通广播FM103.9",
      "type": "feed",
      "url": "rsshub://tingtingfm/program/EOAonLJy7G"
    }
  ],
  "view": 4
}
```
