# 律动 BlockBeats - 新闻快讯

## Coverage
`index-only`

## Route
- Namespace: `theblockbeats`
- Namespace Name: `律动 BlockBeats`
- Route Path: `/theblockbeats/:channel?/:original?`
- Route Name: `新闻快讯`
- Example: `/theblockbeats/newsflash`
- URL: `www.theblockbeats.info`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Fatpandac, jameshih, DIYgod`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
|    快讯   |   文章  |
| :-------: | :-----: |
| newsflash | article |

| 全部 | 深度 | 精选 | 热点追踪 |
| :--: | :--: | :--: | :------: |
|      |  -2  |   1  |     2    |

## Parameters
- `channel`: {"default": "newsflash", "description": "类型", "options": [{"label": "快讯", "value": "newsflash"}, {"label": "文章", "value": "article"}]}
- `original`: {"default": "0", "description": "文章类型，仅 `channel` 为 `article` 时有效", "options": [{"label": "全部", "value": "0"}, {"label": "深度", "value": "1"}, {"label": "精选", "value": "2"}, {"label": "热点追踪", "value": "3"}]}


## Features
_None_

## Radar
### Rule 1
- `title`: `文章`
- `source`:
  - `www.theblockbeats.info/article`
- `target`: `/article`
### Rule 2
- `title`: `快讯`
- `source`:
  - `www.theblockbeats.info/newsflash`
- `target`: `/newsflash`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "|    快讯   |   文章  |\n| :-------: | :-----: |\n| newsflash | article |\n\n| 全部 | 深度 | 精选 | 热点追踪 |\n| :--: | :--: | :--: | :------: |\n|      |  -2  |   1  |     2    |",
  "example": "/theblockbeats/newsflash",
  "heat": 810,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac",
    "jameshih",
    "DIYgod"
  ],
  "name": "新闻快讯",
  "parameters": {
    "channel": {
      "default": "newsflash",
      "description": "类型",
      "options": [
        {
          "label": "快讯",
          "value": "newsflash"
        },
        {
          "label": "文章",
          "value": "article"
        }
      ]
    },
    "original": {
      "default": "0",
      "description": "文章类型，仅 `channel` 为 `article` 时有效",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "深度",
          "value": "1"
        },
        {
          "label": "精选",
          "value": "2"
        },
        {
          "label": "热点追踪",
          "value": "3"
        }
      ]
    }
  },
  "path": "/:channel?/:original?",
  "radar": [
    {
      "source": [
        "www.theblockbeats.info/article"
      ],
      "target": "/article",
      "title": "文章"
    },
    {
      "source": [
        "www.theblockbeats.info/newsflash"
      ],
      "target": "/newsflash",
      "title": "快讯"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "TheBlockBeats - 快讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72541715399995392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theblockbeats.info/newsflash",
      "title": "TheBlockBeats - 快讯",
      "type": "feed",
      "url": "rsshub://theblockbeats/newsflash/0"
    },
    {
      "description": "TheBlockBeats - 文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53870861878019072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theblockbeats.info/article",
      "title": "TheBlockBeats - 文章",
      "type": "feed",
      "url": "rsshub://theblockbeats/article/1"
    }
  ],
  "view": 0
}
```
