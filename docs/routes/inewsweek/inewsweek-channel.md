# 中国新闻周刊 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `inewsweek`
- Namespace Name: `中国新闻周刊`
- Route Path: `/inewsweek/:channel`
- Route Name: `栏目`
- Example: `/inewsweek/survey`
- URL: `inewsweek.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `changren-wcr`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
提取文章全文。

| 封面  | 时政     | 社会    | 经济    | 国际  | 调查   | 人物   |
| ----- | -------- | ------- | ------- | ----- | ------ | ------ |
| cover | politics | society | finance | world | survey | people |

## Parameters
- `channel`: 栏目


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
  - `inewsweek.cn/:channel`
  - `inewsweek.cn/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "提取文章全文。\n\n| 封面  | 时政     | 社会    | 经济    | 国际  | 调查   | 人物   |\n| ----- | -------- | ------- | ------- | ----- | ------ | ------ |\n| cover | politics | society | finance | world | survey | people |",
  "example": "/inewsweek/survey",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 396,
  "location": "index.ts",
  "maintainers": [
    "changren-wcr"
  ],
  "name": "栏目",
  "parameters": {
    "channel": "栏目"
  },
  "path": "/:channel",
  "radar": [
    {
      "source": [
        "inewsweek.cn/:channel",
        "inewsweek.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国新闻周刊--调查 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52911553597762560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://news.inewsweek.cn/survey",
      "title": "中国新闻周刊--调查",
      "type": "feed",
      "url": "rsshub://inewsweek/survey"
    },
    {
      "description": "中国新闻周刊--国际 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66134229854672896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://news.inewsweek.cn/world",
      "title": "中国新闻周刊--国际",
      "type": "feed",
      "url": "rsshub://inewsweek/world"
    }
  ]
}
```
