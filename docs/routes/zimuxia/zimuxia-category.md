# FIX 字幕侠 - 分类

## Coverage
`index-only`

## Route
- Namespace: `zimuxia`
- Namespace Name: `FIX 字幕侠`
- Route Path: `/zimuxia/:category?`
- Route Name: `分类`
- Example: `/zimuxia`
- URL: `zimuxia.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| ALL | FIX 德语社 | 欧美剧集 | 欧美电影 | 综艺 & 纪录 | FIX 日语社 | FIX 韩语社 | FIX 法语社 |
| --- | ---------- | -------- | -------- | ----------- | ---------- | ---------- | ---------- |
|     | 昆仑德语社 | 欧美剧集 | 欧美电影 | 综艺纪录    | fix 日语社 | fix 韩语社 | fix 法语社 |

## Parameters
- `category`: 分类，见下表，默认为 ALL


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
    "multimedia"
  ],
  "description": "| ALL | FIX 德语社 | 欧美剧集 | 欧美电影 | 综艺 & 纪录 | FIX 日语社 | FIX 韩语社 | FIX 法语社 |\n| --- | ---------- | -------- | -------- | ----------- | ---------- | ---------- | ---------- |\n|     | 昆仑德语社 | 欧美剧集 | 欧美电影 | 综艺纪录    | fix 日语社 | fix 韩语社 | fix 法语社 |",
  "example": "/zimuxia",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为 ALL"
  },
  "path": "/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "ALL - FIX字幕侠 - Powered by RSSHub",
      "errorAt": "2025-07-23T01:28:07.673Z",
      "errorMessage": "[GET] \"https://www.zimuxia.cn/我们的作品?\": <no response> fetch failed (getaddrinfo ENOTFOUND www.zimuxia.cn)\n",
      "id": "112773725092189184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "ALL - FIX字幕侠",
      "type": "feed",
      "url": "rsshub://zimuxia"
    },
    {
      "description": "欧美电影 - FIX字幕侠 - Powered by RSSHub",
      "errorAt": "2025-07-23T01:53:19.792Z",
      "errorMessage": "[GET] \"https://www.zimuxia.cn/我们的作品?cat=%E6%AC%A7%E7%BE%8E%E7%94%B5%E5%BD%B1\": <no response> fetch failed (Connect Timeout Error (attempted address: www.zimuxia.cn:443, timeout: 10000ms))\n",
      "id": "132389145495522304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "欧美电影 - FIX字幕侠",
      "type": "feed",
      "url": "rsshub://zimuxia/%E6%AC%A7%E7%BE%8E%E7%94%B5%E5%BD%B1"
    }
  ]
}
```
