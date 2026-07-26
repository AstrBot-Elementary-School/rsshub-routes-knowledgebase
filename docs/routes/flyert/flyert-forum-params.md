# 飞客茶馆 - 会员说

## Coverage
`index-only`

## Route
- Namespace: `flyert`
- Namespace Name: `飞客茶馆`
- Route Path: `/flyert/forum/:params{.+}?`
- Route Name: `会员说`
- Example: `/flyert/forum`
- URL: `www.flyert.com.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [酒店集团优惠](https://www.flyert.com.cn/forum.php?mod=forumdisplay\&sum=all\&fid=all\&catid=322\&filter=sortid\&sortid=144\&searchsort=1\&youhui_type=19)，网址为 `https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19`。截取 `https://www.flyert.com.cn/forum.php?` 到末尾的部分 `mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19` **进行 UrlEncode 编码** 后作为参数填入，此时路由为 [`/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226`](https://rsshub.app/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226)。
:::

## Parameters
- `params`: 参数，默认为空，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.flyert.com.cn/forum.php`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n若订阅 [酒店集团优惠](https://www.flyert.com.cn/forum.php?mod=forumdisplay\\&sum=all\\&fid=all\\&catid=322\\&filter=sortid\\&sortid=144\\&searchsort=1\\&youhui_type=19)，网址为 `https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19`。截取 `https://www.flyert.com.cn/forum.php?` 到末尾的部分 `mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19` **进行 UrlEncode 编码** 后作为参数填入，此时路由为 [`/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226`](https://rsshub.app/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226)。\n:::",
  "example": "/flyert/forum",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 45,
  "location": "forum.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "会员说",
  "parameters": {
    "params": "参数，默认为空，可在对应分类页 URL 中找到"
  },
  "path": "/forum/:params{.+}?",
  "radar": [
    {
      "source": [
        "www.flyert.com.cn/forum.php"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "交流与境外信用卡,美国信用卡相关的信用卡产品、办卡申请、刷卡消费、额度提升、优惠活动、网上支付、分期付款、积分礼品、银行网银、账单还款等的各类业务。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126631276578882560",
      "image": "https://ptf.flyertrip.com/template/comiis_nby/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.flyert.com.cn/forum.php?mod=forumdisplay&fid=228&filter=lastpost&orderby=dateline&subtypeid=1222",
      "title": "飞客 - 信用卡 - 海外用卡 - 全部分类 - 港澳用卡 - 最新发文",
      "type": "feed",
      "url": "rsshub://flyert/forum/mod%3Dforumdisplay%26fid%3D228%26filter%3Dlastpost%26orderby%3Ddateline%26subtypeid%3D1222"
    },
    {
      "description": "交流与境外信用卡,美国信用卡相关的信用卡产品、办卡申请、刷卡消费、额度提升、优惠活动、网上支付、分期付款、积分礼品、银行网银、账单还款等的各类业务。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126630731344783360",
      "image": "https://ptf.flyertrip.com/template/comiis_nby/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.flyert.com.cn/forum.php?mod=forumdisplay&fid=228",
      "title": "飞客 - 信用卡 - 海外用卡 - 全部分类 - 全部二级分类",
      "type": "feed",
      "url": "rsshub://flyert/forum/mod%3Dforumdisplay%26fid%3D228"
    }
  ],
  "url": "www.flyert.com.cn"
}
```
