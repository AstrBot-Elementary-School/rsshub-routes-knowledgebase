# 哔哩哔哩 bilibili - 番剧

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/bangumi/media/:mediaid/:embed?`
- Route Name: `番剧`
- Example: `/bilibili/bangumi/media/9192`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, nuomi1`
- Source Location: `bangumi.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mediaid`: 番剧媒体 id, 番剧主页 URL 中获取
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/bangumi/media/9192",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 420,
  "location": "bangumi.ts",
  "maintainers": [
    "DIYgod",
    "nuomi1"
  ],
  "name": "番剧",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "mediaid": "番剧媒体 id, 番剧主页 URL 中获取"
  },
  "path": "/bangumi/media/:mediaid/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "看机智的凡人小子韩立如何稳健发展、步步为营，战魔道、夺至宝、驰骋星海、快意恩仇，成为纵横三界的强者。他日仙界重相逢，一声道友尽沧桑。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61414387750364160",
      "image": "https://i0.hdslb.com/bfs/bangumi/image/19a2d01429bcba6b31791277c016e0d1aa465974.png",
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/bangumi/media/md28223043",
      "title": "凡人修仙传",
      "type": "feed",
      "url": "rsshub://bilibili/bangumi/media/28223043"
    },
    {
      "description": "遙遠的未來，人類在荒廢的大地上建設了移動要塞都市“種植園”，並謳歌著文明。在那當中建造的駕駛員居住設施“米斯特汀”，通稱“鳥籠”。孩子們就住在那裡，他們被告知的使命，只有戰鬥。敵人是一切都被謎團覆蓋的巨大生命體“叫龍”。為了對抗尚未見過的敵人，孩子們乘上被稱為“FRANXX”的機器人。有一位曾被稱作神童的少年。代號016。名字是廣。但他現在卻跌落穀底。是不被人需要的存在。如果沒有乘上FRANXX，就如同不存在一樣。在這樣的廣面前，某天，一位被稱作02的神秘少女出現了。她的額頭，長著兩根豔麗的角。“——找到了哦，我的DARLING” - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61347726361821184",
      "image": "https://i0.hdslb.com/bfs/bangumi/becda7a59d0fe317c51a6e357857cffca20fa0d4.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/bangumi/media/md9192",
      "title": "DARLING in the FRANXX（僅限港澳台地區）",
      "type": "feed",
      "url": "rsshub://bilibili/bangumi/media/9192"
    }
  ],
  "view": 3
}
```
