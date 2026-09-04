# 云听 - 专辑

## Coverage
`index-only`

## Route
- Namespace: `radio`
- Namespace Name: `云听`
- Route Path: `/radio/album/:id`
- Route Name: `专辑`
- Example: `/radio/album/15682090498666`
- URL: `radio.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `album.ts`
- Source Module: `_None_`

## Description
如果订阅 [中国相声榜](https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666`，可以得到 `columnId` 为 `15682090498666`

所以对应路由为 [`/radio/album/15682090498666`](https://rsshub.app/radio/album/15682090498666)

::: tip
部分专辑不适用该路由，此时可以尝试 [节目](#yun-ting-jie-mu) 路由
:::

## Parameters
- `id`: 专辑 id，可在对应专辑页面的 URL 中找到


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
  "description": "如果订阅 [中国相声榜](https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666`，可以得到 `columnId` 为 `15682090498666`\n\n所以对应路由为 [`/radio/album/15682090498666`](https://rsshub.app/radio/album/15682090498666)\n\n::: tip\n部分专辑不适用该路由，此时可以尝试 [节目](#yun-ting-jie-mu) 路由\n:::",
  "example": "/radio/album/15682090498666",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 59,
  "location": "album.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专辑",
  "parameters": {
    "id": "专辑 id，可在对应专辑页面的 URL 中找到"
  },
  "path": "/album/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "相声起源于华北地区的民间说唱曲艺，在明朝即已盛行。经清朝时期的发展直至民国初年，逐渐从一个人摹拟口技发展成为单口笑话。一种类型的单口相声，后来逐步发展为多种类型的单口相声、对口相声、群口相声，综合为一体。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79070847873399808",
      "image": "https://ytmedia.radio.cn/CCYT%2F202303%2F14%2F16%2FmxhxuqiSgEKo0FygXxrDXIgb9AnXDkq32023031416709.jpg",
      "ownerUserId": null,
      "siteUrl": "https://ytweb.radio.cn/share/albumDetail?columnId=15682090498666",
      "title": "云听 - 中国相声榜",
      "type": "feed",
      "url": "rsshub://radio/album/15682090498666"
    },
    {
      "description": "纵论天下，闲话三分，细品是非功过，总结成败得失，欢迎收听《易中天品三国》。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "91729125068344320",
      "image": "https://ytmedia.radio.cn/CCYT%2F201910%2F24%2F11%2FduHn3qQZwCOAW7deD6hPXpYYRbNApf2SEThIm91qr2019102411186.jpg",
      "ownerUserId": null,
      "siteUrl": "https://ytweb.radio.cn/share/albumDetail?columnId=15682083075196",
      "title": "云听 - 易中天品三国",
      "type": "feed",
      "url": "rsshub://radio/album/15682083075196"
    }
  ]
}
```
