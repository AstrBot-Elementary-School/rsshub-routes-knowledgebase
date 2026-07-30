# 虎嗅 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/huxiu/article`
- Route Name: `资讯`
- Example: `/huxiu/article`
- URL: `huxiu.com/article`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW, nczitzk, TimoYoung`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
| 视频 | 前沿科技 | 车与出行 | 商业消费 | 社会文化 |
| ---- | -------- | -------- | -------- | -------- |
| 10   | 105      | 21       | 103      | 106      |

| 金融财经 | 出海 | 国际热点 | 游戏娱乐 | 健康 |
| -------- | ---- | -------- | -------- | ---- |
| 115      | 114  | 107      | 22       | 118  |

| 书影音 | 医疗 | 3C 数码 | 观点 | 其他 |
| ------ | ---- | ------- | ---- | ---- |
| 119    | 120  | 121     | 122  | 123  |

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `huxiu.com/article`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 视频 | 前沿科技 | 车与出行 | 商业消费 | 社会文化 |\n| ---- | -------- | -------- | -------- | -------- |\n| 10   | 105      | 21       | 103      | 106      |\n\n| 金融财经 | 出海 | 国际热点 | 游戏娱乐 | 健康 |\n| -------- | ---- | -------- | -------- | ---- |\n| 115      | 114  | 107      | 22       | 118  |\n\n| 书影音 | 医疗 | 3C 数码 | 观点 | 其他 |\n| ------ | ---- | ------- | ---- | ---- |\n| 119    | 120  | 121     | 122  | 123  |",
  "example": "/huxiu/article",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 602,
  "location": "channel.ts",
  "maintainers": [
    "HenryQW",
    "nczitzk",
    "TimoYoung"
  ],
  "name": "资讯",
  "parameters": {},
  "path": [
    "/article",
    "/channel/:id?"
  ],
  "radar": [
    {
      "source": [
        "huxiu.com/article"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "虎嗅资讯-全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41423034778090498",
      "image": "https://static.huxiucdn.com/common/image/logo/logo_200.png",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/article",
      "title": "虎嗅资讯-全部",
      "type": "feed",
      "url": "rsshub://huxiu/article"
    }
  ],
  "url": "huxiu.com/article"
}
```
