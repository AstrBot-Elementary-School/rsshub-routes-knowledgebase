# 腾讯 - 更新日志

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/tencent/qq/sdk/changelog/:platform`
- Route Name: `更新日志`
- Example: `/tencent/qq/sdk/changelog/iOS`
- URL: `tencent.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nuomi1`
- Source Location: `qq/sdk/changelog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `platform`: 平台，iOS / Android


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
    "program-update"
  ],
  "example": "/tencent/qq/sdk/changelog/iOS",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "qq/sdk/changelog.ts",
  "maintainers": [
    "nuomi1"
  ],
  "name": "更新日志",
  "parameters": {
    "platform": "平台，iOS / Android"
  },
  "path": "/qq/sdk/changelog/:platform",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Android SDK 历史变更 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66062279192217600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wiki.connect.qq.com/android_sdk%E5%8E%86%E5%8F%B2%E5%8F%98%E6%9B%B4",
      "title": "Android SDK 历史变更",
      "type": "feed",
      "url": "rsshub://tencent/qq/sdk/changelog/Android"
    },
    {
      "description": "iOS SDK 历史变更 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58163407301475328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wiki.connect.qq.com/ios_sdk%E5%8E%86%E5%8F%B2%E5%8F%98%E6%9B%B4",
      "title": "iOS SDK 历史变更",
      "type": "feed",
      "url": "rsshub://tencent/qq/sdk/changelog/iOS"
    }
  ]
}
```
