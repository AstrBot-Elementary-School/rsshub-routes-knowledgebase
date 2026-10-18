# 新浪 - 科技 - 科学探索

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/sina/discovery/:type`
- Route Name: `科技 - 科学探索`
- Example: `/sina/discovery/zx`
- URL: `finance.sina.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `discovery.ts`
- Source Module: `_None_`

## Description
| 最新 | 天文航空 | 动物植物 | 自然地理 | 历史考古 | 生命医学 | 生活百科 | 科技前沿 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| zx   | twhk     | dwzw     | zrdl     | lskg     | smyx     | shbk     | kjqy     |

## Parameters
- `type`: 订阅分区类型，见下表


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
  "description": "| 最新 | 天文航空 | 动物植物 | 自然地理 | 历史考古 | 生命医学 | 生活百科 | 科技前沿 |\n| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| zx   | twhk     | dwzw     | zrdl     | lskg     | smyx     | shbk     | kjqy     |",
  "example": "/sina/discovery/zx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "discovery.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "科技 - 科学探索",
  "parameters": {
    "type": "订阅分区类型，见下表"
  },
  "path": "/discovery/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "最新-新浪科技科学探索 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64850724380424192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tech.sina.com.cn/discovery/",
      "title": "最新-新浪科技科学探索",
      "type": "feed",
      "url": "rsshub://sina/discovery/zx"
    },
    {
      "description": "科技前沿-新浪科技科学探索 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68505818791555072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tech.sina.com.cn/discovery/",
      "title": "科技前沿-新浪科技科学探索",
      "type": "feed",
      "url": "rsshub://sina/discovery/kjqy"
    }
  ]
}
```
