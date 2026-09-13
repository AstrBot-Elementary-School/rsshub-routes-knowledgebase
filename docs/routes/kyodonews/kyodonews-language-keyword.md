# 共同网 - 最新报道

## Coverage
`index-only`

## Route
- Namespace: `kyodonews`
- Namespace Name: `共同网`
- Route Path: `/kyodonews/:language?/:keyword?`
- Route Name: `最新报道`
- Example: `/kyodonews`
- URL: `china.kyodonews.net`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Rongronggg9`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
`keyword` 为关键词，由于共同网有许多关键词并不在主页列出，此处不一一列举，可从关键词页的 URL 的最后一级路径中提取。如 `日中关系` 的关键词页 URL 为 `https://china.kyodonews.net/news/japan-china_relationship`, 则将 `japan-china_relationship` 填入 `keyword`。特别地，当填入 `rss` 时，将从共同网官方 RSS 中抓取文章；略去时，将从首页抓取最新报道 (注意：首页更新可能比官方 RSS 稍慢)。

## Parameters
- `language`: 语言: `china` = 简体中文 (默认), `tchina` = 繁體中文
- `keyword`: 关键词


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
  - `china.kyodonews.net/news/:keyword`
  - `china.kyodonews.net/`
- `target`: `/china/:keyword?`
### Rule 2
- `source`:
  - `tchina.kyodonews.net/news/:keyword`
  - `tchina.kyodonews.net/`
- `target`: `/tchina/:keyword?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "`keyword` 为关键词，由于共同网有许多关键词并不在主页列出，此处不一一列举，可从关键词页的 URL 的最后一级路径中提取。如 `日中关系` 的关键词页 URL 为 `https://china.kyodonews.net/news/japan-china_relationship`, 则将 `japan-china_relationship` 填入 `keyword`。特别地，当填入 `rss` 时，将从共同网官方 RSS 中抓取文章；略去时，将从首页抓取最新报道 (注意：首页更新可能比官方 RSS 稍慢)。",
  "example": "/kyodonews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 158,
  "location": "index.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "最新报道",
  "parameters": {
    "keyword": "关键词",
    "language": "语言: `china` = 简体中文 (默认), `tchina` = 繁體中文"
  },
  "path": "/:language?/:keyword?",
  "radar": [
    {
      "source": [
        "china.kyodonews.net/news/:keyword",
        "china.kyodonews.net/"
      ],
      "target": "/china/:keyword?"
    },
    {
      "source": [
        "tchina.kyodonews.net/news/:keyword",
        "tchina.kyodonews.net/"
      ],
      "target": "/tchina/:keyword?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "日本一般社团法人共同通讯社（以下简称共同社）成立于1945年，由日本全国的报社及日本放送协会（NHK）等媒体共同设立，独立于政府，旨在准确公正地报道国内外的新闻，在满足国民知情权的同时，为增进国际社会的相互理解做贡献。共同社除了在国内各都道府县政府所在地及其他主要城市拥有分社和分局之外，在海外的约40座主要城市也设有总局或分局，员工总数约1600人。作为立足于亚洲、代表日本的综合性国际通讯社，共同社在原有的日语和英语服务的基础上，于2001年设立了中文新闻网站&ldquo;共同网&rdquo;，并在建社60周年的2005年成立了中文新闻部门，扩大了中文信息服务，致力于提供各领域最新消息，希望以自身的努力增进华语圈读者对日本社会的了解。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56542470518821888",
      "image": "https://china-kyodo.ismcdn.jp/common/images/apple-touch-icon-180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://china.kyodonews.net/",
      "title": "共同网",
      "type": "feed",
      "url": "rsshub://kyodonews"
    },
    {
      "description": "共同网在网上：每日国际，日本新闻，日本新闻，从报纸，国家和地方新闻报道，突发新闻更新，技术新闻，体育，评论，上市。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66155011953127424",
      "image": "https://china-kyodo.ismcdn.jp/common/images/apple-touch-icon-180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://china.kyodonews.net/list/feed/rss4news",
      "title": "新闻 - 共同网",
      "type": "feed",
      "url": "rsshub://kyodonews/china/rss"
    }
  ]
}
```
