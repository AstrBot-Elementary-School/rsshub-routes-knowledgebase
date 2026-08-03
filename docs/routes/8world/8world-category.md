# 8 视界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `8world`
- Namespace Name: `8 视界`
- Route Path: `/8world/:category?`
- Route Name: `分类`
- Example: `/8world/realtime`
- URL: `8world.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类                   | id             |
| ---------------------- | -------------- |
| 即时 REALTIME          | realtime       |
| 新加坡 SINGAPORE       | singapore      |
| 东南亚 SOUTH-EAST ASIA | southeast-asia |
| 中港台 GREATER CHINA   | greater-china  |
| 国际 WORLD             | world          |
| 财经 FINANCE           | finance        |
| 体育 SPORTS            | sports         |
| 社团 COMMUNITY         | community      |

## Parameters
- `category`: 分类 id，见下表，默认为即时 REALTIME


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
  "description": "| 分类                   | id             |\n| ---------------------- | -------------- |\n| 即时 REALTIME          | realtime       |\n| 新加坡 SINGAPORE       | singapore      |\n| 东南亚 SOUTH-EAST ASIA | southeast-asia |\n| 中港台 GREATER CHINA   | greater-china  |\n| 国际 WORLD             | world          |\n| 财经 FINANCE           | finance        |\n| 体育 SPORTS            | sports         |\n| 社团 COMMUNITY         | community      |",
  "example": "/8world/realtime",
  "heat": 16,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类 id，见下表，默认为即时 REALTIME"
  },
  "path": "/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "即时新闻 - 掌握新加坡、东南亚和国际新闻，一览最新新闻大事 - 8world - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69384991748864011",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.8world.com/realtime",
      "title": "即时新闻 - 掌握新加坡、东南亚和国际新闻，一览最新新闻大事 - 8world",
      "type": "feed",
      "url": "rsshub://8world"
    },
    {
      "description": "中港台新闻 - 了解与关注中国大陆、台湾及香港新闻与时事 - 8world - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79335306854878213",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.8world.com/greater-china",
      "title": "中港台新闻 - 了解与关注中国大陆、台湾及香港新闻与时事 - 8world",
      "type": "feed",
      "url": "rsshub://8world/greater-china"
    }
  ]
}
```
