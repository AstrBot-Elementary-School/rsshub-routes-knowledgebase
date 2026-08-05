# 小宇宙 - 播客

## Coverage
`index-only`

## Route
- Namespace: `xiaoyuzhou`
- Namespace Name: `小宇宙`
- Route Path: `/xiaoyuzhou/podcast/:id`
- Route Name: `播客`
- Example: `/xiaoyuzhou/podcast/6021f949a789fca4eff4492c`
- URL: `xiaoyuzhoufm.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `hondajojo, jtsang4, pseudoyu, cscnk52`
- Source Location: `podcast.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 播客 id 或单集 id，可以在小宇宙播客的 URL 中找到


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
  - `xiaoyuzhoufm.com/podcast/:id`
  - `xiaoyuzhoufm.com/episode/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/xiaoyuzhou/podcast/6021f949a789fca4eff4492c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 51837,
  "location": "podcast.ts",
  "maintainers": [
    "hondajojo",
    "jtsang4",
    "pseudoyu",
    "cscnk52"
  ],
  "name": "播客",
  "parameters": {
    "id": "播客 id 或单集 id，可以在小宇宙播客的 URL 中找到"
  },
  "path": "/podcast/:id",
  "radar": [
    {
      "source": [
        "xiaoyuzhoufm.com/podcast/:id",
        "xiaoyuzhoufm.com/episode/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "《知行小酒馆》是有知有行出品的一档分享投资与生活的播客节目。我们关注投资理财，更关注怎样更好地生活。在我们看来，投资成功，是我们变成一个更好的人之后，自然的结果。 如果你对节目有任何建议，或者有推荐的嘉宾，或者只是想与我们分享你和小酒馆的故事，可以给我们发邮件，来信请寄：allinthebeer@gmail.com 如果你有长期投资的需求，非常欢迎下载 有知有行App，里面有你一定能读懂的好课程《投资第一课》，也有专业的投资观察《知行黑板报》，更有我们全员持有的好产品「长钱账户」「稳钱账户」「海外长钱」，人称「长稳海三胞胎」。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54349807700270080",
      "image": "https://image.xyzcdn.net/Fso6ZPHSi62eZJOLhorcqpx8TEwv.jpg@small",
      "ownerUserId": null,
      "siteUrl": "https://www.xiaoyuzhoufm.com/podcast/6013f9f58e2f7ee375cf4216",
      "title": "知行小酒馆",
      "type": "feed",
      "url": "rsshub://xiaoyuzhou/podcast/6013f9f58e2f7ee375cf4216"
    },
    {
      "description": "商业不枯燥。 财经媒体人和互联网产品老兵，跟你讲述商业背后的故事。 来杯半拿铁，咱们边喝边唠。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41371367532304384",
      "image": "https://image.xyzcdn.net/FlZXHELEin8JN9xIrT3IMsQQo1M0.png@small",
      "ownerUserId": null,
      "siteUrl": "https://www.xiaoyuzhoufm.com/podcast/62382c1103bea1ebfffa1c00",
      "title": "半拿铁 | 商业沉浮录",
      "type": "feed",
      "url": "rsshub://xiaoyuzhou/podcast/62382c1103bea1ebfffa1c00"
    }
  ],
  "url": "xiaoyuzhoufm.com/",
  "view": 4
}
```
