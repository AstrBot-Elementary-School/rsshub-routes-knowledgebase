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
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HPDOfmqjUI4VlDbeoLDbrBs_J6EWOj4XZ6U14ESZ&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzg5Mjc3NzQzMA%3D%3D%26mid%3D2247575188%26idx%3D1%26sn%3Dd6e784c98df5d33335415e22b7d08fc0\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HPjOfmqjKbovPe4qGXKrXFYE5waYJA-9XvdRkOtD&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzg5Mjc3NzQzMA%3D%3D%26mid%3D2247575188%26idx%3D1%26sn%3Dd6e784c98df5d33335415e22b7d08fc0\n",
      "id": "87572776852626432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/homepage?__biz=Mzg5Mjc3NzQzMA==&hid=3",
      "title": "|10万＋推荐",
      "type": "feed",
      "url": "rsshub://wechat/mp/homepage/Mzg5Mjc3NzQzMA==/3"
    },
    {
      "description": "|李厚辰·专栏 - Powered by RSSHub",
      "errorAt": "2025-08-12T08:16:13.890Z",
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HAH1Umqj9BOntK7OZny3JQNqiKkfMRjA5QvPQnqE&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzA3MDM3NjE5NQ%3D%3D%26mid%3D2650852529%26idx%3D1%26sn%3D19e0f66ad91816137a5b16d64d6969d7\n",
      "id": "58707616374334464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=16",
      "title": "|李厚辰·专栏",
      "type": "feed",
      "url": "rsshub://wechat/mp/homepage/MzA3MDM3NjE5NQ==/16"
    }
  ]
}
```
