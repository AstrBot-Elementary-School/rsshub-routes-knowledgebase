# 格隆汇 - 最热文章

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/hot-article/:type?`
- Route Name: `最热文章`
- Example: `/gelonghui/hot-article`
- URL: `gelonghui.com/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `nczitzk`
- Source Location: `hot-article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "`day` 为日排行，`week` 为周排行，默认为 `day`", "options": [{"label": "日排行", "value": "day"}, {"label": "周排行", "value": "week"}]}


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
  - `gelonghui.com/`
- `target`: `/hot-article`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/gelonghui/hot-article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2005,
  "location": "hot-article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "最热文章",
  "parameters": {
    "type": {
      "description": "`day` 为日排行，`week` 为周排行，默认为 `day`",
      "options": [
        {
          "label": "日排行",
          "value": "day"
        },
        {
          "label": "周排行",
          "value": "week"
        }
      ]
    }
  },
  "path": "/hot-article/:type?",
  "radar": [
    {
      "source": [
        "gelonghui.com/"
      ],
      "target": "/hot-article"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "格隆汇为中国投资者出海投资及中国公司出海融资,提供海外投资,港股开户行情,科创板股票发行数据、资讯、研究、交易等一站式服务,目前业务范围主要涉及港股与美股两大市场,未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61616343170046976",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/",
      "title": "最热文章 - 日排行 - 格隆汇",
      "type": "feed",
      "url": "rsshub://gelonghui/hot-article"
    },
    {
      "description": "格隆汇为中国投资者出海投资及中国公司出海融资,提供海外投资,港股开户行情,科创板股票发行数据、资讯、研究、交易等一站式服务,目前业务范围主要涉及港股与美股两大市场,未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72494824717739008",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/",
      "title": "最热文章 - 日排行 - 格隆汇",
      "type": "feed",
      "url": "rsshub://gelonghui/hot-article/day"
    }
  ],
  "url": "gelonghui.com/",
  "view": 0
}
```
