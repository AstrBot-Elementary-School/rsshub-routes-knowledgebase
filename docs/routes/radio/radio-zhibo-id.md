# 云听 - 直播

## Coverage
`index-only`

## Route
- Namespace: `radio`
- Namespace Name: `云听`
- Route Path: `/radio/zhibo/:id`
- Route Name: `直播`
- Example: `/radio/zhibo/1395528`
- URL: `radio.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `zhibo.ts`
- Source Module: `_None_`

## Description
如果订阅 [新闻和报纸摘要](http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528)，其 URL 为 `http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528`，可以得到 `name` 为 `1395528`

所以对应路由为 [`/radio/zhibo/1395528`](https://rsshub.app/radio/zhibo/1395528)

::: tip
查看更多电台直播节目，可前往 [电台直播](http://www.radio.cn/pc-portal/erji/radioStation.html)
:::

## Parameters
- `id`: 直播 id，可在对应点播页面的 URL 中找到


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
  "description": "如果订阅 [新闻和报纸摘要](http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528)，其 URL 为 `http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528`，可以得到 `name` 为 `1395528`\n\n所以对应路由为 [`/radio/zhibo/1395528`](https://rsshub.app/radio/zhibo/1395528)\n\n::: tip\n查看更多电台直播节目，可前往 [电台直播](http://www.radio.cn/pc-portal/erji/radioStation.html)\n:::",
  "example": "/radio/zhibo/1395528",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 230,
  "location": "zhibo.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "直播",
  "parameters": {
    "id": "直播 id，可在对应点播页面的 URL 中找到"
  },
  "path": "/zhibo/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "云听 - 新闻和报纸摘要 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66710109444054016",
      "image": "https://www.radio.cn/pc-portal/image/icon_32.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528",
      "title": "云听 - 新闻和报纸摘要",
      "type": "feed",
      "url": "rsshub://radio/zhibo/1395528"
    },
    {
      "description": "云听 - Music Flow 音乐流 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "103011206332568576",
      "image": "https://www.radio.cn/pc-portal/image/icon_32.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1432818",
      "title": "云听 - Music Flow 音乐流",
      "type": "feed",
      "url": "rsshub://radio/zhibo/1432818"
    }
  ]
}
```
