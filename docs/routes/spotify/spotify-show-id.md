# Spotify - Show/Podcasts

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/show/:id`
- Route Name: `Show/Podcasts`
- Example: `/spotify/show/5CfCWKI5pZ28U0uOzXkDHe`
- URL: `open.spotify.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `caiohsramos, pseudoyu`
- Source Location: `show.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Show ID


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/show/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/spotify/show/5CfCWKI5pZ28U0uOzXkDHe",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_ID"
      },
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_SECRET"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2115,
  "location": "show.ts",
  "maintainers": [
    "caiohsramos",
    "pseudoyu"
  ],
  "name": "Show/Podcasts",
  "parameters": {
    "id": "Show ID"
  },
  "path": "/show/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/show/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "《圆桌派》是一档最下饭的聊天综艺节目，由著名媒体人、文化名嘴窦文涛携手优酷“看理想”倾力打造。不设剧本，即兴聊天，平等视角，智慧分享。本频道非官方频道，音视频版权归原节目和平台所有。本频道由粉丝Eddy个人搬运自费维护，非盈利目的，如有冒犯或侵权可留言下架。欢迎您动动手指在上方对本频道评分及评论，五星好评是对本频道最大的支持！目前本频道收录了圆桌派第一（2016）、二（2017）、三（2018）、四（2019）、五（2021）、六（2022）、七（2024）、八（2025）季已播出的全部内容，以及各季间的番外篇包括女生派（S1）、武侠派（S2）、讲究派（S3）、时光派（S3）、跨越派（S4）、新春派（S5）、什锦派（S5）、直播连麦（S5）。第八季已完结。欢迎订阅本频道以获得最新更新提醒，本频道支持按季查找以便您回看往期节目。 节目网址：https://open.spotify.com/show/100jfJAxtcJdl8xfjvGXzr RSS订阅地址：https://anchor.fm/s/10bfbcf64/podcast/rss 备用节目网址：https://eddy.firstory.io 备用RSS订阅地址：https://feed.firstory.me/rss/user/cl7zkcpvy0a0h01wi8uxbccdv - Powered by RSSHub",
      "errorAt": "2026-03-12T06:33:59.207Z",
      "errorMessage": "Spotify public RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n502 \nSpotify public RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\nSpotify public RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n[GET] \"https://api.spotify.com/v1/shows/100jfJAxtcJdl8xfjvGXzr?market=US\": 403 Forbidden\n",
      "id": "60246541475182592",
      "image": "https://i.scdn.co/image/ab6765630000ba8a0e1f2c95d90d979152f3faac",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/show/100jfJAxtcJdl8xfjvGXzr",
      "title": "圆桌派",
      "type": "feed",
      "url": "rsshub://spotify/show/100jfJAxtcJdl8xfjvGXzr"
    },
    {
      "description": "当下中国最有趣的谈话都是在私下进行的。《不明白播客》希望把有趣的谈话分享给世界各地的中文听众，在这个黑暗、混乱的时代发出一点光亮和温度。这个播客是几位专业新闻记者联合发起的个人项目，不代表我们供职的机构。取名不明白是因为在这个魔幻的国度有太多不符合常理值得探究的事情。我们希望每周能就一个话题进行深入、不设限制的讨论。欢迎收听、订阅和分享。 Hosted on Acast. See acast.com/privacy for more information. - Powered by RSSHub",
      "errorAt": "2026-03-11T03:50:47.604Z",
      "errorMessage": "[GET] \"https://api.spotify.com/v1/shows/5CV2Xo4kHE6Lf1iZBzsrP2?market=US\": 403 Forbidden\n",
      "id": "54407761127659520",
      "image": "https://i.scdn.co/image/ab6765630000ba8ad4f083c27e19d2258bc9b02c",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/show/5CV2Xo4kHE6Lf1iZBzsrP2",
      "title": "不明白播客",
      "type": "feed",
      "url": "rsshub://spotify/show/5CV2Xo4kHE6Lf1iZBzsrP2"
    }
  ],
  "view": 4
}
```
