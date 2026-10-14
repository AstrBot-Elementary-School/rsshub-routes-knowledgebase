# NIO - Radio

## Coverage
`index-only`

## Route
- Namespace: `nio`
- Namespace Name: `NIO`
- Route Path: `/nio/nioradio/:albumid`
- Route Name: `Radio`
- Example: `/nio/nioradio/5`
- URL: `nio.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `marcosteam`
- Source Location: `nioradio.ts`
- Source Module: `_None_`

## Description
::: tip
**如何获取电台 ID？**
打开蔚来 APP 后，点击 “此地”→“NIO Radio”，找到自己想要转换为播客的专辑，分享后在生成的链接中找到`container_id=`后方的数字即可。
常见电台 ID：

| 电台名称             | 电台 ID |
| :------------------- | :------ |
| 资讯充电站（早间版） | 5       |
| 资讯充电站（晚间版） | 23      |
| E 次元财经报         | 148     |
| 塞萌不塞车           | 661     |
| 乐行记               | 11      |
| Weekend Dance        | 547     |

:::

## Parameters
- `albumid`: 电台专辑 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n**如何获取电台 ID？**\n打开蔚来 APP 后，点击 “此地”→“NIO Radio”，找到自己想要转换为播客的专辑，分享后在生成的链接中找到`container_id=`后方的数字即可。\n常见电台 ID：\n\n| 电台名称             | 电台 ID |\n| :------------------- | :------ |\n| 资讯充电站（早间版） | 5       |\n| 资讯充电站（晚间版） | 23      |\n| E 次元财经报         | 148     |\n| 塞萌不塞车           | 661     |\n| 乐行记               | 11      |\n| Weekend Dance        | 547     |\n\n:::",
  "example": "/nio/nioradio/5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 7,
  "location": "nioradio.ts",
  "maintainers": [
    "marcosteam"
  ],
  "name": "Radio",
  "parameters": {
    "albumid": "电台专辑 ID"
  },
  "path": "/nioradio/:albumid",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NIO Radio - 资讯充电站·早间版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "178093579122011136",
      "image": "https://cdn-udp-public.nio.com/nio-muses-admin/_Y4wF-7h51mF2ECxeInPX/EMU9UvtjILmpVTHMuv1Mo",
      "ownerUserId": null,
      "siteUrl": "https://www.nio.com/",
      "title": "NIO Radio - 资讯充电站·早间版",
      "type": "feed",
      "url": "rsshub://nio/nioradio/5"
    },
    {
      "description": "NIO Radio - 塞萌不塞车·精选 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "178094914038467584",
      "image": "https://cdn-udp-public.nio.com/nio-muses-admin/bMGHa8RRbtqGGqfo8tmOn/5wm5HPc5scQ3dyGzkXiRu",
      "ownerUserId": null,
      "siteUrl": "https://www.nio.com/",
      "title": "NIO Radio - 塞萌不塞车·精选",
      "type": "feed",
      "url": "rsshub://nio/nioradio/661"
    }
  ]
}
```
