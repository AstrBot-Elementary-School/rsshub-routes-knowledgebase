# 微信小程序 - 公众号栏目 (非推送 & 历史消息)

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/mp/homepage/:biz/:hid/:cid?`
- Route Name: `公众号栏目 (非推送 & 历史消息)`
- Example: `/wechat/mp/homepage/MzA3MDM3NjE5NQ==/16`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `MisteryMonster`
- Source Location: `mp.ts`
- Source Module: `_None_`

## Description
只适用拥有首页模板 (分享链接带有 homepage) 的公众号。例如从公众号分享出来的链接为 `https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4`，`biz` 为 `MzA3MDM3NjE5NQ==`，`hid` 为 `4`。

有些页面里会有分栏， `cid` 可以通过元素选择器选中栏目查看`data-index`。如[链接](https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==\&hid=4)里的 `京都职人` 栏目的 `cid` 为 `0`，`文艺时光` 栏目的 `cid` 为 `2`。如果不清楚的话最左边的栏目为`0`，其右方栏目依次递增 `1`。

## Parameters
- `biz`: 公众号id
- `hid`: 分页id
- `cid`: 页内栏目


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
  "description": "只适用拥有首页模板 (分享链接带有 homepage) 的公众号。例如从公众号分享出来的链接为 `https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4`，`biz` 为 `MzA3MDM3NjE5NQ==`，`hid` 为 `4`。\n\n有些页面里会有分栏， `cid` 可以通过元素选择器选中栏目查看`data-index`。如[链接](https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==\\&hid=4)里的 `京都职人` 栏目的 `cid` 为 `0`，`文艺时光` 栏目的 `cid` 为 `2`。如果不清楚的话最左边的栏目为`0`，其右方栏目依次递增 `1`。",
  "example": "/wechat/mp/homepage/MzA3MDM3NjE5NQ==/16",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "mp.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "公众号栏目 (非推送 & 历史消息)",
  "parameters": {
    "biz": "公众号id",
    "cid": "页内栏目",
    "hid": "分页id"
  },
  "path": "/mp/homepage/:biz/:hid/:cid?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "|10万＋推荐 - Powered by RSSHub",
      "errorAt": "2025-08-14T05:48:47.732Z",
      "errorMessage": "Failed to fetch\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HCq9l2qjElhiWad4YFn2SaXkvgShIKHPz3vbhMIh&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzg5Mjc3NzQzMA%3D%3D%26mid%3D2247567388%26idx%3D1%26sn%3D4f0cb572b5cd8eeeb27f36402732e873\n",
      "id": "87572776852626432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/homepage?__biz=Mzg5Mjc3NzQzMA==&hid=3",
      "title": "|10万＋推荐",
      "type": "feed",
      "url": "rsshub://wechat/mp/homepage/Mzg5Mjc3NzQzMA==/3"
    },
    {
      "description": "|ShowMeAI 日报➕周刊 - Powered by RSSHub",
      "errorAt": "2025-04-22T15:34:59.019Z",
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HH8ZfWqjmW48XY4st-2gCwQkcPZ4txrf1aUns_a4&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzg2OTYyMTcwMw%3D%3D%26mid%3D2247535110%26idx%3D1%26sn%3D92bfe13456f2ac5125eff34e78f21519\n",
      "id": "58378671255288864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/homepage?__biz=Mzg2OTYyMTcwMw==&hid=2",
      "title": "|ShowMeAI 日报➕周刊",
      "type": "feed",
      "url": "rsshub://wechat/mp/homepage/Mzg2OTYyMTcwMw==/2/"
    }
  ]
}
```
