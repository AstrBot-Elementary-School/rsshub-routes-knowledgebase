# 少数派 sspai - 会员社区

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/prime/community`
- Route Name: `会员社区`
- Example: `/sspai/prime/community`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `mintyfrankie`
- Source Location: `prime-community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "少数派会员账号认证 token。获取方式：登陆后打开少数派会员社区界面，打开浏览器开发者工具中 “网络”(Network) 选项卡，筛选 URL 找到任一个地址为 `sspai.com/api` 开头的请求，点击检查其 “消息头”，在 “请求头” 中找到Authorization字段，将其值复制填入配置即可。你的配置应该形如 `SSPAI_BEARERTOKEN: 'Bearer eyJxxxx......xx_U8'`。", "name": "SSPAI_BEARERTOKEN", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/community`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/prime/community",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "少数派会员账号认证 token。获取方式：登陆后打开少数派会员社区界面，打开浏览器开发者工具中 “网络”(Network) 选项卡，筛选 URL 找到任一个地址为 `sspai.com/api` 开头的请求，点击检查其 “消息头”，在 “请求头” 中找到Authorization字段，将其值复制填入配置即可。你的配置应该形如 `SSPAI_BEARERTOKEN: 'Bearer eyJxxxx......xx_U8'`。",
        "name": "SSPAI_BEARERTOKEN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "prime-community.ts",
  "maintainers": [
    "mintyfrankie"
  ],
  "name": "会员社区",
  "path": "/prime/community",
  "radar": [
    {
      "source": [
        "sspai.com/community"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "少数派会员社区 - Powered by RSSHub",
      "errorAt": "2025-11-06T02:28:22.630Z",
      "errorMessage": "[GET] \"https://sspai.com/api/v1/community/page/get\": 401 Unauthorized\n[GET] \"https://sspai.com/api/v1/community/page/get\": 401 Unauthorized\n[GET] \"https://sspai.com/api/v1/community/page/get\": 401 Unauthorized\n",
      "id": "68530810459857920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/community",
      "title": "少数派会员社区",
      "type": "feed",
      "url": "rsshub://sspai/prime/community"
    }
  ]
}
```
