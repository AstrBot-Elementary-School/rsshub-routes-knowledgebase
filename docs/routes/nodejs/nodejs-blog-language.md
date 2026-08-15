# Node.js - News

## Coverage
`index-only`

## Route
- Namespace: `nodejs`
- Namespace Name: `Node.js`
- Route Path: `/nodejs/blog/:language?`
- Route Name: `News`
- Example: `/nodejs/blog`
- URL: `nodejs.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
Official RSS Source: <https://nodejs.org/en/feed/blog.xml>

| العربية | Catalan | Deutsch | Español | زبان فارسی |
| ------- | ------- | ------- | ------- | ---------- |
| ar      | ca      | de      | es      | fa         |

| Français | Galego | Italiano | 日本語 | 한국어 |
| -------- | ------ | -------- | ------ | ------ |
| fr       | gl     | it       | ja     | ko     |

| Português do Brasil | limba română | Русский | Türkçe | Українська |
| ------------------- | ------------ | ------- | ------ | ---------- |
| pt-br               | ro           | ru      | tr     | uk         |

| 简体中文 | 繁體中文 |
| -------- | -------- |
| zh-cn    | zh-tw    |

## Parameters
- `language`: Language, see below, en by default


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
  - `nodejs.org/:language/blog`
  - `nodejs.org/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Official RSS Source: <https://nodejs.org/en/feed/blog.xml>\n\n| العربية | Catalan | Deutsch | Español | زبان فارسی |\n| ------- | ------- | ------- | ------- | ---------- |\n| ar      | ca      | de      | es      | fa         |\n\n| Français | Galego | Italiano | 日本語 | 한국어 |\n| -------- | ------ | -------- | ------ | ------ |\n| fr       | gl     | it       | ja     | ko     |\n\n| Português do Brasil | limba română | Русский | Türkçe | Українська |\n| ------------------- | ------------ | ------- | ------ | ---------- |\n| pt-br               | ro           | ru      | tr     | uk         |\n\n| 简体中文 | 繁體中文 |\n| -------- | -------- |\n| zh-cn    | zh-tw    |",
  "example": "/nodejs/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "language": "Language, see below, en by default"
  },
  "path": "/blog/:language?",
  "radar": [
    {
      "source": [
        "nodejs.org/:language/blog",
        "nodejs.org/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "News - Node.js - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98341488375760896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nodejs.org/en/blog",
      "title": "News - Node.js",
      "type": "feed",
      "url": "rsshub://nodejs/blog"
    },
    {
      "description": "News - Node.js - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72473659742656512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nodejs.org/zh-cn/blog",
      "title": "News - Node.js",
      "type": "feed",
      "url": "rsshub://nodejs/blog/zh-cn"
    }
  ]
}
```
