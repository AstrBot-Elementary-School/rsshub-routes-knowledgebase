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
  "heat": 848,
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
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HBnAfmqjGM7pkMnoRJzt7s5JCX98smLBbc18VvTe&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247509829%26idx%3D2%26sn%3D1260885a2e19cea7bd88769f1922460b\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HB3AfmqjyB3dw5Ln5OLKZjstCN76KEqhwG1lhyWy&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247509797%26idx%3D1%26sn%3Defdbac68042f181575db3c51e7f76084\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HCvAfmqjsVbCTQPtaKAg31vNUa29BIGyzkKx-AaY&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247509885%26idx%3D1%26sn%3D1a1cd2f1535bc91267ad7d54d26e84d2\n",
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
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HCQwfWqjg0ZF8yKmbwuWvEPsuXElyxe6tHUZT9Qw&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzAxMjYyMzkwOA%3D%3D%26mid%3D2247536145%26idx%3D2%26sn%3Df59c40b1cdf08b6f8bda9d6637d101e5\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HDMwfWqjLuUiFqaqsUjc-VyDjvopBY8K_I8yXER7&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzAxMjYyMzkwOA%3D%3D%26mid%3D2247536101%26idx%3D1%26sn%3D88fbf5d2dbbeb42a8c164b6aae96097c\n",
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
