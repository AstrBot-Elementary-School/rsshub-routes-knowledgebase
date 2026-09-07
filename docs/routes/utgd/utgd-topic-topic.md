# UNTAG - 专题

## Coverage
`index-only`

## Route
- Namespace: `utgd`
- Namespace Name: `UNTAG`
- Route Path: `/utgd/topic/:topic?`
- Route Name: `专题`
- Example: `/utgd/topic/在线阅读专栏`
- URL: `utgd.net/topic`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 在线阅读专栏 | 卡片笔记专题 |
| ------------ | ------------ |

更多专栏请见 [专题广场](https://utgd.net/topic)

## Parameters
- `topic`: 专题，默认为在线阅读专栏


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `utgd.net/topic`
  - `utgd.net/`
- `target`: `/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 在线阅读专栏 | 卡片笔记专题 |\n| ------------ | ------------ |\n\n更多专栏请见 [专题广场](https://utgd.net/topic)",
  "example": "/utgd/topic/在线阅读专栏",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专题",
  "parameters": {
    "topic": "专题，默认为在线阅读专栏"
  },
  "path": "/topic/:topic?",
  "radar": [
    {
      "source": [
        "utgd.net/topic",
        "utgd.net/"
      ],
      "target": "/topic/:topic"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "在线阅读如同一场狩猎，所涉搜寻信息、过滤标记、翻译解释、剪藏收集和高亮批注等环节，均值得深入讨论。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84413185965128704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://utgd.net/topic",
      "title": "UNTAG - 在线阅读专栏",
      "type": "feed",
      "url": "rsshub://utgd/topic"
    },
    {
      "description": "在线阅读如同一场狩猎，所涉搜寻信息、过滤标记、翻译解释、剪藏收集和高亮批注等环节，均值得深入讨论。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84480433803877376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://utgd.net/topic",
      "title": "UNTAG - 在线阅读专栏",
      "type": "feed",
      "url": "rsshub://utgd/topic/%E5%9C%A8%E7%BA%BF%E9%98%85%E8%AF%BB%E4%B8%93%E6%A0%8F"
    }
  ],
  "url": "utgd.net/topic"
}
```
