# 微信小程序 - 公众号文章话题 Tag

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/mp/msgalbum/:biz/:aid`
- Route Name: `公众号文章话题 Tag`
- Example: `/wechat/mp/msgalbum/MzA3MDM3NjE5NQ==/1375870284640911361`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `MisteryMonster`
- Source Location: `msgalbum.ts`
- Source Module: `_None_`

## Description
一些公众号（如看理想）会在微信文章里添加 Tag ，点入 Tag 的链接如 `https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzA3MDM3NjE5NQ==&action=getalbum&album_id=1375870284640911361`，其中`biz` 为 `MzA3MDM3NjE5NQ==`，`aid` 为 `1375870284640911361`。

## Parameters
- `biz`: 公众号id
- `aid`: Tag id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "一些公众号（如看理想）会在微信文章里添加 Tag ，点入 Tag 的链接如 `https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzA3MDM3NjE5NQ==&action=getalbum&album_id=1375870284640911361`，其中`biz` 为 `MzA3MDM3NjE5NQ==`，`aid` 为 `1375870284640911361`。",
  "example": "/wechat/mp/msgalbum/MzA3MDM3NjE5NQ==/1375870284640911361",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 844,
  "location": "msgalbum.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "公众号文章话题 Tag",
  "parameters": {
    "aid": "Tag id",
    "biz": "公众号id"
  },
  "path": "/mp/msgalbum/:biz/:aid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "PaperAgent|LLM热点Paper - Powered by RSSHub",
      "errorAt": "2025-07-23T12:13:10.406Z",
      "errorMessage": "Failed to fetch\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HIkLlmqj667yRgbl2HNaoGCzSOwN7ElxR1AOW2dI&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247510344%26idx%3D2%26sn%3Dfb783822a60a5c04a578ff5d515962c0\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HI4LlmqjWJL3uOsp85b1gJwretZQnI_vwDQlBXBs&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247510389%26idx%3D1%26sn%3D7350fad291d64236df87c1709af89073\n",
      "id": "55818057211386897",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/appmsgalbum?__biz=Mzk0MTYzMzMxMA&action=getalbum&album_id=3256352785986404355",
      "title": "PaperAgent|LLM热点Paper",
      "type": "feed",
      "url": "rsshub://wechat/mp/msgalbum/Mzk0MTYzMzMxMA/3256352785986404355"
    },
    {
      "description": "Ots安全|威胁分析 - Powered by RSSHub",
      "errorAt": "2025-07-23T05:08:30.331Z",
      "errorMessage": "Failed to fetch\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HG7olWqjVlOoArXdVw3xAjSltq7zx0HMcZLEK-aU&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzAxMjYyMzkwOA%3D%3D%26mid%3D2247536459%26idx%3D2%26sn%3D297054b94c0bcd8b697bdb66ae9918e0\n",
      "id": "57679399689810944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzAxMjYyMzkwOA==&action=getalbum&album_id=2839958662130647042",
      "title": "Ots安全|威胁分析",
      "type": "feed",
      "url": "rsshub://wechat/mp/msgalbum/MzAxMjYyMzkwOA==/2839958662130647042"
    }
  ]
}
```
