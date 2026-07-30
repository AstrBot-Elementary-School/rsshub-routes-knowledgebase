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
      "errorAt": null,
      "errorMessage": null,
      "id": "60836830967846935",
      "image": "http://i0.hdslb.com/bfs/manga-static/e79378436e02fd7f227b901efb9fe79c2df9499c.jpg",
      "ownerUserId": null,
      "siteUrl": "https://manga.bilibili.com/detail/mc26551",
      "title": "蓝溪镇 - 哔哩哔哩漫画",
      "type": "feed",
      "url": "rsshub://bilibili/manga/update/26551"
    },
    {
      "description": "在打倒了魔王的勇者一行人当中，魔法使芙莉莲是精灵，她和其他三人有不一样的地方。 生活在“之后”的世界里，她感受到了什么—— 留下来的人们所编织的葬送与祈祷又意味着什么—— 故事从“冒险的结束”开始。 这是讲述英雄们的活法的，后日谈奇幻作品！ - Powered by RSSHub",
      "errorAt": "2026-07-28T22:26:17.373Z",
      "errorMessage": "Cannot read properties of null (reading 'author_name')\n",
      "id": "81498058940083200",
      "image": "https://i0.hdslb.com/bfs/manga-static/b85cfd1921ba7e74ff8cbbbc5f102191b6045c92.jpg",
      "ownerUserId": null,
      "siteUrl": "https://manga.bilibili.com/detail/mc30460",
      "title": "葬送的芙莉莲 - 哔哩哔哩漫画",
      "type": "feed",
      "url": "rsshub://bilibili/manga/update/30460"
    }
  ]
}
```
