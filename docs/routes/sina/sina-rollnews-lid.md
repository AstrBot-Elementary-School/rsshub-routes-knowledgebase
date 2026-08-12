# 新浪 - 滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/sina/rollnews/:lid?`
- Route Name: `滚动新闻`
- Example: `/sina/rollnews`
- URL: `finance.sina.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `xyqfer`
- Source Location: `rollnews.ts`
- Source Module: `_None_`

## Description
| 全部 | 国内 | 国际 | 社会 | 体育 | 娱乐 | 军事 | 科技 | 财经 | 股市 | 美股 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 2509 | 2510 | 2511 | 2669 | 2512 | 2513 | 2514 | 2515 | 2516 | 2517 | 2518 |

## Parameters
- `lid`: 分区 id，可在 URL 中找到，默认为 `2509`


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
  "description": "| 全部 | 国内 | 国际 | 社会 | 体育 | 娱乐 | 军事 | 科技 | 财经 | 股市 | 美股 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 2509 | 2510 | 2511 | 2669 | 2512 | 2513 | 2514 | 2515 | 2516 | 2517 | 2518 |",
  "example": "/sina/rollnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "rollnews.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "滚动新闻",
  "parameters": {
    "lid": "分区 id，可在 URL 中找到，默认为 `2509`"
  },
  "path": "/rollnews/:lid?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新浪全部滚动新闻 - Powered by RSSHub",
      "errorAt": "2026-08-11T08:08:54.339Z",
      "errorMessage": "Failed to fetch\n",
      "id": "67473482043971584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.sina.com.cn/roll/#pageid=153&lid=2509&k=&num=50&page=1",
      "title": "新浪全部滚动新闻",
      "type": "feed",
      "url": "rsshub://sina/rollnews"
    },
    {
      "description": "新浪全部滚动新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86770785762500608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.sina.com.cn/roll/#pageid=153&lid=2509&k=&num=50&page=1",
      "title": "新浪全部滚动新闻",
      "type": "feed",
      "url": "rsshub://sina/rollnews/2509"
    }
  ]
}
```
