# 北京社科网 - 通用

## Coverage
`index-only`

## Route
- Namespace: `bjsk`
- Namespace Name: `北京社科网`
- Route Path: `/bjsk/:path?`
- Route Name: `通用`
- Example: `/bjsk/newslist-1394-1474-0`
- URL: `bjsk.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
路径处填写对应页面 URL 中 `https://www.bjsk.org.cn/` 和 `.html` 之间的字段。下面是一个例子。

若订阅 [社科资讯 > 社科要闻](https://www.bjsk.org.cn/newslist-1394-1474-0.html) 则将对应页面 URL `https://www.bjsk.org.cn/newslist-1394-1474-0.html` 中 `https://www.bjsk.org.cn/` 和 `.html` 之间的字段 `newslist-1394-1474-0` 作为路径填入。此时路由为 [`/bjsk/newslist-1394-1474-0`](https://rsshub.app/bjsk/newslist-1394-1474-0)
:::

## Parameters
- `path`: 路径，默认为 `newslist-1486-0-0`


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
    "government"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `https://www.bjsk.org.cn/` 和 `.html` 之间的字段。下面是一个例子。\n\n若订阅 [社科资讯 > 社科要闻](https://www.bjsk.org.cn/newslist-1394-1474-0.html) 则将对应页面 URL `https://www.bjsk.org.cn/newslist-1394-1474-0.html` 中 `https://www.bjsk.org.cn/` 和 `.html` 之间的字段 `newslist-1394-1474-0` 作为路径填入。此时路由为 [`/bjsk/newslist-1394-1474-0`](https://rsshub.app/bjsk/newslist-1394-1474-0)\n:::",
  "example": "/bjsk/newslist-1394-1474-0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为 `newslist-1486-0-0`"
  },
  "path": "/:path?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
