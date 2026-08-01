# 哔哩哔哩 bilibili - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/manga/update/:comicid`
- Route Name: `漫画更新`
- Example: `/bilibili/manga/update/26009`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `manga-update.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `comicid`: 漫画 id, 可在 URL 中找到, 支持带有`mc`前缀


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
  - `manga.bilibili.com/detail/:comicid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/manga/update/26009",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 216,
  "location": "manga-update.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "漫画更新",
  "parameters": {
    "comicid": "漫画 id, 可在 URL 中找到, 支持带有`mc`前缀"
  },
  "path": "/manga/update/:comicid",
  "radar": [
    {
      "source": [
        "manga.bilibili.com/detail/:comicid"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "《罗小黑战记》君清篇~~讲述战争年代的老君、玄离和清凝的故事。为你展现不一样的妖神世界~ - Powered by RSSHub",
      "errorAt": "2026-07-27T04:35:57.138Z",
      "errorMessage": "Cannot read properties of null (reading 'author_name')\n",
      "id": "60836830967846935",
      "image": "http://i0.hdslb.com/bfs/manga-static/e79378436e02fd7f227b901efb9fe79c2df9499c.jpg",
      "ownerUserId": null,
      "siteUrl": "https://manga.bilibili.com/detail/mc26551",
      "title": "蓝溪镇 - 哔哩哔哩漫画",
      "type": "feed",
      "url": "rsshub://bilibili/manga/update/26551"
    },
    {
      "description": "【此漫画的翻译由杭州翻翻公司提供】被骗得负债累累，过着贫困生活的少年电次，与链锯恶魔波奇塔一起做恶魔猎人勉强活了下去。最底层的生活，因为一次残忍的背叛全都改变了！！让恶魔寄宿在自己的身体去狩猎恶魔，新时代黑暗英雄故事，开幕！！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52425851550270464",
      "image": "https://i0.hdslb.com/bfs/manga-static/fef4e807325510365fb87389a4e2c1695360249a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://manga.bilibili.com/detail/mc28376",
      "title": "Chainsaw Man（电锯人） - 哔哩哔哩漫画",
      "type": "feed",
      "url": "rsshub://bilibili/manga/update/28376"
    }
  ]
}
```
