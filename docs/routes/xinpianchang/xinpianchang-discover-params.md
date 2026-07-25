# 新片场 - 发现

## Coverage
`index-only`

## Route
- Namespace: `xinpianchang`
- Namespace Name: `新片场`
- Route Path: `/xinpianchang/discover/:params?`
- Route Name: `发现`
- Example: `/xinpianchang/discover`
- URL: `xinpianchang.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
跳转到欲订阅的分类页，将 URL 的 `/discover` 到末尾的部分填入 `params` 参数。

如 [全部原创视频作品](https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score) 的 URL 为 `https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score`，其 `/discover` 到末尾的部分为 `article-0-0-all-all-0-0-score`，所以对应的路由为 [/xinpianchang/discover/article-0-0-all-all-0-0-score](https://rsshub.app/xinpianchang/discover/article-0-0-all-all-0-0-score)。
:::

## Parameters
- `params`: 参数，可在对应分类页 URL 中找到，默认为 `article-0-0-all-all-0-0-score` ，即全部


## Features
- `requireConfig`: false
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
    "new-media"
  ],
  "description": "::: tip\n跳转到欲订阅的分类页，将 URL 的 `/discover` 到末尾的部分填入 `params` 参数。\n\n如 [全部原创视频作品](https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score) 的 URL 为 `https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score`，其 `/discover` 到末尾的部分为 `article-0-0-all-all-0-0-score`，所以对应的路由为 [/xinpianchang/discover/article-0-0-all-all-0-0-score](https://rsshub.app/xinpianchang/discover/article-0-0-all-all-0-0-score)。\n:::",
  "example": "/xinpianchang/discover",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 121,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "发现",
  "parameters": {
    "params": "参数，可在对应分类页 URL 中找到，默认为 `article-0-0-all-all-0-0-score` ，即全部"
  },
  "path": [
    "/discover/:params?",
    "/:params?"
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新片场社区汇聚全球优秀创作人和海量精选原创短视频作品,覆盖广告,宣传片,剧情短片,创意混剪,婚礼,纪录片,特殊摄影,旅拍,Vlog,影视干货教程,音乐MV等无水印高清视频案例学习下载。 - Powered by RSSHub",
      "errorAt": "2025-08-15T00:11:41.108Z",
      "errorMessage": "[GET] \"https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score\": 403 Forbidden\n",
      "id": "61586602339364911",
      "image": "https://oss-xpc0.xpccdn.com/Upload/edu/2022/06/02629881408a499.png",
      "ownerUserId": null,
      "siteUrl": "https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score",
      "title": "新片场·原创视频作品精选",
      "type": "feed",
      "url": "rsshub://xinpianchang/discover"
    },
    {
      "description": "新片场社区汇聚全球优秀全球精选内容创作人和海量精选全球精选原创短视频作品,在线观看超高清和4K视频及全球精选作品创作教程,下载无水印视频案例和学习交流。 - Powered by RSSHub",
      "errorAt": "2025-08-15T22:14:30.949Z",
      "errorMessage": "[GET] \"https://www.xinpianchang.com/discover/article-9999-0\": 403 Forbidden\n",
      "id": "72472464679796736",
      "image": "https://oss-xpc0.xpccdn.com/Upload/edu/2022/06/02629881408a499.png",
      "ownerUserId": null,
      "siteUrl": "https://www.xinpianchang.com/discover/article-9999-0",
      "title": "新片场·全球精选",
      "type": "feed",
      "url": "rsshub://xinpianchang/discover/article-9999-0"
    }
  ]
}
```
