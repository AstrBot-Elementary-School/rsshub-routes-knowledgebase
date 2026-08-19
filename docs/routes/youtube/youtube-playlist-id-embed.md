# YouTube - Playlist

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/playlist/:id/:embed?`
- Route Name: `Playlist`
- Example: `/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `HenryQW`
- Source Location: `playlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: YouTube playlist id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY", "optional": true}]
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
    "social-media",
    "popular"
  ],
  "example": "/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)",
        "name": "YOUTUBE_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1554,
  "location": "playlist.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Playlist",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "id": "YouTube playlist id"
  },
  "path": "/playlist/:id/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "这是中国调查记者王志安在YouTube上开设的节目，每天关注中国重要的时政和社会新闻。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63845323989307392",
      "image": "https://i.ytimg.com/pl_c/PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq/studio_square_thumbnail.jpg?sqp=CJaNjtQG-oaymwEICNAFENAFSFqi85f_AwYImOKvqwY=&rs=AOn4CLD8PvmidJ0cmiEWKe6ZQZyqsZ7PdA",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/playlist?list=PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq",
      "title": "王局拍案 by 王志安 - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/playlist/PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq"
    },
    {
      "description": "1、专业视角解读，带你构建全球宏观和大类资产分析框架。课程围绕利率、汇率、股票、黄金、商品、衍生品等资产类别，用专业视角拆解金融热点，助你理解市场运行的逻辑。 2、全球宏观视野，带你看透大类资产FICC新变化。紧跟市场最新动态，从当下发生的现象切入，讲解背后的深层原理、机制及分析方法。以每节10-20分钟的时间，直击市场热点要点，以最短的时间让你有所启发。 3、买方投资思维，带你看清全球金融市场热点背后的真相。案例导向，事件切入，点评从现象到原理、到复盘到展望。无论你是刚入行的新人还是跟踪市场的老手，都能在课程中有所收获。 4、金融市场导师，带你读懂重要市场议题。付鹏拥有10余年的海外对冲基金工作经验，对全球资本市场大类资产之间的轮动，以及全球宏观经济的把握有着深刻的理解。面对纷繁的市场现象，他有能力也有经验，筛选出值得你花时间了解的市场关注点，并转化成听得懂、记得住的课程内容产品。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93660941816522752",
      "image": "https://i.ytimg.com/vi/m7tfUrsJsrw/hqdefault.jpg?sqp=-oaymwExCNACELwBSFryq4qpAyMIARUAAIhCGAHwAQH4Af4JgALQBYoCDAgAEAEYYyBjKGMwDw==&rs=AOn4CLAzP1etQerVVHfma9Gn-2IH3klTkA",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/playlist?list=PLjzImVTiIJZn_esvTZ7KH5RCngxPOc7-i",
      "title": "付鹏说 by Since1982 - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/playlist/PLjzImVTiIJZn_esvTZ7KH5RCngxPOc7-i"
    }
  ],
  "view": 3
}
```
