# Web3Caff - 发现

## Coverage
`index-only`

## Route
- Namespace: `web3caff`
- Namespace Name: `Web3Caff`
- Route Path: `/web3caff/:path{.+}?`
- Route Name: `发现`
- Example: `/web3caff/zh/archives/category/news_zh`
- URL: `web3caff.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
路径处填写对应页面 URL 中 `https://web3caff.com/` 后的字段。下面是一个例子。

若订阅 [叙事 - Web3Caff](https://web3caff.com/zh/archives/category/news_zh) 则将对应页面 URL <https://web3caff.com/zh/archives/category/news_zh> 中 `https://web3caff.com/` 后的字段 `zh/archives/category/news_zh` 作为路径填入。此时路由为 [`/web3caff/zh/archives/category/news_zh`](https://rsshub.app/web3caff/zh/archives/category/news_zh)

## Parameters
- `path`: 路径，默认为首页


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "路径处填写对应页面 URL 中 `https://web3caff.com/` 后的字段。下面是一个例子。\n\n若订阅 [叙事 - Web3Caff](https://web3caff.com/zh/archives/category/news_zh) 则将对应页面 URL <https://web3caff.com/zh/archives/category/news_zh> 中 `https://web3caff.com/` 后的字段 `zh/archives/category/news_zh` 作为路径填入。此时路由为 [`/web3caff/zh/archives/category/news_zh`](https://rsshub.app/web3caff/zh/archives/category/news_zh)",
  "example": "/web3caff/zh/archives/category/news_zh",
  "heat": 14,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "发现",
  "parameters": {
    "path": "路径，默认为首页"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Web3Caff - 以深度视角探索 Web3 产业创新 - Powered by RSSHub",
      "errorAt": "2026-01-19T10:52:21.578Z",
      "errorMessage": "[GET] \"https://web3caff.com\": <no response> fetch failed (C052C906B37F0000:error:0A000410:SSL routines:ssl3_read_bytes:ssl/tls alert handshake failure:../deps/openssl/openssl/ssl/record/rec_layer_s3.c:918:SSL alert number 40\n)\n",
      "id": "54902946701684736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://web3caff.com/",
      "title": "Web3Caff - 以深度视角探索 Web3 产业创新",
      "type": "feed",
      "url": "rsshub://web3caff"
    }
  ]
}
```
