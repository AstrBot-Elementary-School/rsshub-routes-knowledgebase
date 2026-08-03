# Quicker - 动作分享

## Coverage
`index-only`

## Route
- Namespace: `quicker`
- Namespace Name: `Quicker`
- Route Path: `/quicker/share/:category?`
- Route Name: `动作分享`
- Example: `/quicker/share/Recent`
- URL: `getquicker.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `share.ts`
- Source Module: `_None_`

## Description
| 动作库最新更新 | 动作库最多赞 | 动作库新动作 | 动作库最近赞 |
| -------------- | ------------ | ------------ | ------------ |
| Recent         | Recommended  | NewActions   | RecentLiked  |

| 子程序      | 扩展热键  | 文本指令     |
| ----------- | --------- | ------------ |
| SubPrograms | PowerKeys | TextCommands |

## Parameters
- `category`: 分类，见下表，默认为动作库最新更新


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
  - `getquicker.net/Share/:category`
  - `getquicker.net/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 动作库最新更新 | 动作库最多赞 | 动作库新动作 | 动作库最近赞 |\n| -------------- | ------------ | ------------ | ------------ |\n| Recent         | Recommended  | NewActions   | RecentLiked  |\n\n| 子程序      | 扩展热键  | 文本指令     |\n| ----------- | --------- | ------------ |\n| SubPrograms | PowerKeys | TextCommands |",
  "example": "/quicker/share/Recent",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "share.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "动作分享",
  "parameters": {
    "category": "分类，见下表，默认为动作库最新更新"
  },
  "path": "/share/:category?",
  "radar": [
    {
      "source": [
        "getquicker.net/Share/:category",
        "getquicker.net/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新动作 - Quicker - Powered by RSSHub",
      "errorAt": "2026-07-21T13:45:17.468Z",
      "errorMessage": "[GET] \"https://getquicker.netundefined\": <no response> fetch failed (getaddrinfo ENOTFOUND getquicker.netundefined)\n",
      "id": "77063565001164800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://getquicker.net/Share/Recent",
      "title": "最新动作 - Quicker",
      "type": "feed",
      "url": "rsshub://quicker/share/Recent"
    },
    {
      "description": "受欢迎的动作 - Quicker - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78683255211688960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://getquicker.net/Share/Recommended",
      "title": "受欢迎的动作 - Quicker",
      "type": "feed",
      "url": "rsshub://quicker/share/Recommended"
    }
  ]
}
```
