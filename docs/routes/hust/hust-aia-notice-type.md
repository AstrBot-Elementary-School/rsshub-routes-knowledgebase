# 华中科技大学 - 人工智能和自动化学院通知

## Coverage
`index-only`

## Route
- Namespace: `hust`
- Namespace Name: `华中科技大学`
- Route Path: `/hust/aia/notice/:type?`
- Route Name: `人工智能和自动化学院通知`
- Example: `/hust/aia/notice`
- URL: `hust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `budui`
- Source Location: `aia/notice.ts`
- Source Module: `_None_`

## Description
| 最新 | 党政 | 科研 | 本科生 | 研究生 | 学工思政 | 离退休 |
| ---- | ---- | ---- | ------ | ------ | -------- | ------ |
|      | dz   | ky   | bk     | yjs    | xgsz     | litui  |

## Parameters
- `type`: 分区，默认为最新通知，可在网页 URL 中找到


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
    "university"
  ],
  "description": "| 最新 | 党政 | 科研 | 本科生 | 研究生 | 学工思政 | 离退休 |\n| ---- | ---- | ---- | ------ | ------ | -------- | ------ |\n|      | dz   | ky   | bk     | yjs    | xgsz     | litui  |",
  "example": "/hust/aia/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "aia/notice.ts",
  "maintainers": [
    "budui"
  ],
  "name": "人工智能和自动化学院通知",
  "parameters": {
    "type": "分区，默认为最新通知，可在网页 URL 中找到"
  },
  "path": [
    "/aia/notice/:type?",
    "/auto/notice/:type?"
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
