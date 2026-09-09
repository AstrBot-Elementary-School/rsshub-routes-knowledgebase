# pixiv - Novel Series

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/novel/series/:id`
- Route Name: `Novel Series`
- Example: `/pixiv/novel/series/11586857`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `SnowAgar25, keocheung`
- Source Location: `novel-series.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Series id, can be found in URL


## Features
- `requireConfig`: [{"description": "\nrefresh_token after Pixiv login, required for accessing R18 novels\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)", "name": "PIXIV_REFRESHTOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pixiv.net/novel/series/:id`
- `target`: `/novel/series/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/pixiv/novel/series/11586857",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "\nrefresh_token after Pixiv login, required for accessing R18 novels\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)",
        "name": "PIXIV_REFRESHTOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "novel-series.ts",
  "maintainers": [
    "SnowAgar25",
    "keocheung"
  ],
  "name": "Novel Series",
  "parameters": {
    "id": "Series id, can be found in URL"
  },
  "path": "/novel/series/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/novel/series/:id"
      ],
      "target": "/novel/series/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "本人是重度NTR粉，在看过琼明后十分震撼，非常喜欢，但可惜剑剑上岸了......于是我打算自己写一本刘皇叔，借鉴了包括琼明神女录、逍遥小散仙等等作品，甚至直接把一些情节改一点抄过来，这我也不藏着掖着，图一乐罢了。大伙看得开心就行。 重点——本书含有巨量NTR要素，厌者退避！！！ - Powered by RSSHub",
      "errorAt": "2026-09-07T14:01:34.934Z",
      "errorMessage": "[GET] \"https://www.pixiv.net/ajax/novel/series/12332549\": 403 Forbidden\n",
      "id": "82250278315604992",
      "image": "https://pixiv.rss3.workers.dev/novel-cover-original/img/2025/07/26/16/42/41/sci12332549_3556a2989bf48590b772e4c024179cfb.png",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/novel/series/12332549",
      "title": "神女逍遥录",
      "type": "feed",
      "url": "rsshub://pixiv/novel/series/12332549"
    },
    {
      "description": "真白未那，小时的青梅，家世神秘的绝美女子大学生，成为了我的女友。 但我却总是能看到她被别的男人寝取幻象。于是，我们两人决定展开禁忌的NTRS游戏。 - Powered by RSSHub",
      "errorAt": "2026-09-07T19:07:27.548Z",
      "errorMessage": "[GET] \"https://www.pixiv.net/ajax/novel/series/12807039\": 403 Forbidden\n",
      "id": "98849096219253760",
      "image": "https://pixiv.rss3.workers.dev/novel-cover-original/img/2024/11/09/20/14/09/sci12807039_c4e913ac38af901bdc05bd1ed9ea1a7e.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/novel/series/12807039",
      "title": "真白未那必须堕落",
      "type": "feed",
      "url": "rsshub://pixiv/novel/series/12807039"
    }
  ]
}
```
