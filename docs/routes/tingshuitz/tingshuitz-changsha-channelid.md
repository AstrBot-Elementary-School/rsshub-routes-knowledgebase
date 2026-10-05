# 停水通知 - 长沙市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/changsha/:channelId?`
- Route Name: `长沙市`
- Example: `/tingshuitz/changsha/78`
- URL: `swj.dl.gov.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `shansing`
- Source Location: `changsha.ts`
- Source Module: `_None_`

## Description
可能仅限于中国大陆服务器访问，以实际情况为准。

| channelId | 分类     |
| --------- | -------- |
| 78        | 计划停水 |
| 157       | 抢修停水 |

## Parameters
- `channelId`: N


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
    "forecast"
  ],
  "description": "可能仅限于中国大陆服务器访问，以实际情况为准。\n\n| channelId | 分类     |\n| --------- | -------- |\n| 78        | 计划停水 |\n| 157       | 抢修停水 |",
  "example": "/tingshuitz/changsha/78",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "changsha.ts",
  "maintainers": [
    "shansing"
  ],
  "name": "长沙市",
  "parameters": {
    "channelId": "N"
  },
  "path": "/changsha/:channelId?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
